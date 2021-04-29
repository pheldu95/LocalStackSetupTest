# LocalStackSetupTest
my bucket name: localstacktest

used these two guides:
https://onexlab-io.medium.com/localstack-s3-e28ad393c09 <--- mainly this one
https://reflectoring.io/aws-localstack/ 

command to setup docker once you make docker-compose file:
docker-compose up

command to setup aws:
aws --endpoint-url=http://localhost:4566 s3 mb s3://localstacktest

command to look at bucket:
aws --endpoint-url=http://localhost:4566 s3 ls <your-bucket-name>