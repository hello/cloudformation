aws cloudformation create-stack --stack-name guide --parameters ParameterKey=WebsiteDomainName,ParameterValue=staging-user.hello.is --template-body file:///$PWD/user-guide/bucket_dns.json

