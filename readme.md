# Lambda to process and image url and save to S3

## setting and running
serverless deploy

serverless invoke --function save --log --data='{ "image_url": "https://assets-cdn.github.com/images/modules/open_graph/github-mark.png", "key": "github.png"}'

[Source] (https://github.com/serverless/examples/tree/master/aws-node-fetch-file-and-store-in-s3)

## output
Serverless: Stack update finished...
Service Information
service: fetch-file-store-s3
stage: dev
region: us-east-1
api keys:
  None
endpoints:
  None
functions:
  fetch-file-store-s3-dev-save: arn:aws:lambda:us-east-1:565003319456:function:fetch-file-store-s3-dev-save

fetch-file-store-s3-dev-serverlessdeploymentbucke-1e1tjh4svi57w