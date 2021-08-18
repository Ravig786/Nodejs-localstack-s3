# Nodejs-localstack-s3
Nodejs-localstack-s3

## To run the project

>>`cmd` -> `docker-compose up -d`

>>`cmd` -> `npm i`

>> `cmd` -> `npm run createbucket`

>>`cmd` ->  `npm run dev`

### To create your own bucket 
>`cmd` ->  `aws --endpoint-url=http://localhost:4566/ s3 mb s3://<BucketName>` or `npm run createbucket` 


