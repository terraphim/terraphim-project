# terraphim-project
Product and project management for terraphim

Driven by Earthly CI:
Create bucket: 
```
earthly --secret-file-path /Users/alexandermikhalev/rust_code/terraphim/op_args -i +publish --region="eu-west-2" --args="s3 mb s3://project-manager-terraphim-kg-ci"
```