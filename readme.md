
# Create Serverless template

Run: ``sls create --template aws-go --path goCazilia``

> https://www.serverless.com/framework/docs/providers/aws/examples/hello-world/go/

Run: `` go mod init <NAME>``  

Run: ``go get github.com/aws/aws-lambda-go/events``

Run: ``go get github.com/aws/aws-lambda-go/lambda``

Add serverless plugin to serverless.yml

```
plugins:
  - serverless-offline
  
```

## How to use serverless offline

https://dev.to/nmk/serverless-offline-golang-setup-11lp


# Serverless support

https://www.serverless.com/blog/framework-example-golang-lambda-support

# CURL: 

- testPost - POST
curl -d '{ok:true}' -H 'Content-Type: application/json' http://localhost:3000/dev/testPost