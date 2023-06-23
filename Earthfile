VERSION 0.7
PROJECT applied-knowledge-systems/terraphim-project

FROM ubuntu:18.04

publish-pipeline:
  PIPELINE
  TRIGGER push main
  TRIGGER pr main
  BUILD +run

prepare: 
  FROM github.com/terraphim/terraphim-logseq-md-parser-simple+build --tag="latest"
  WORKDIR /output
  COPY pages/* .
  RUN mkdir ./data
  RUN /code/logseq-md-parser-simple --path ./
  SAVE ARTIFACT ./data AS LOCAL ./data

  
run:
  FROM github.com/applied-knowledge-systems/aws_op_earthly+login-op
  COPY +prepare/data /data
  ENV AWS_REGION="eu-west-2"
  RUN --no-cache --secret OP_CONNECT_HOST --secret OP_CONNECT_TOKEN op run --env-file="/workspace/aws.env" -- aws s3 sync /data/ s3://project-manager-terraphim-kg-ci/ --acl public-read
          
