VERSION 0.7
PROJECT my-org/terraphim-project

FROM alpine:3.15

some-pipeline:
  PIPELINE
  TRIGGER push main
  TRIGGER pr main
  BUILD +my-build

my-build:
  RUN echo Hello world
          
