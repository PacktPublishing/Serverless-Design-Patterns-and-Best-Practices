
### Get this product for $5

<i>Packt is having its biggest sale of the year. Get this eBook or any other book, video, or course that you like just for $5 each</i>


<b><p align='center'>[Buy now](https://packt.link/9781788623582)</p></b>


<b><p align='center'>[Buy similar titles for just $5](https://subscription.packtpub.com/search)</p></b>



# Serverless Design Patterns and Best Practices
This is the code repository for [Serverless Design Patterns and Best Practices](https://www.packtpub.com/application-development/serverless-design-patterns-and-best-practices?utm_source=github&utm_medium=repository&utm_campaign=9781788620642), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Serverless applications handle many problems that developers face when running systems and servers. The serverless pay-per-invocation model can also result in drastic cost savings, contributing to its popularity and wide usage. While it’s simple to create a basic serverless application, it’s critical to structure your software correctly to ensure it continues to succeed as it grows. Serverless Design Patterns and Best Practices presents design patterns which will be adapted to run in a serverless environment. You will learn how to develop applications that are scalable, fault tolerant, and well tested.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
def divide(event, context):
  params = event.get('queryStringParameters') or {}
  numerator = int(params.get('numerator', 10))
  denominator = int(params.get('denominator', 2))
  body = {
    "message": "Results of %s / %s = %s" % (
      numerator,
      denominator,
      numerator // denominator,
    )
  }
```

Almost all of the examples in this book use the Serverless Framework to manage AWS resources and Lambda functions. Installation instructions for the Serverless Framework can be found at https:/​/​serverless.​com/​framework/​docs/​gettingstarted/​.

In addition to the Serverless Framework, readers will need to have an AWS account to run the examples. For those new to AWS, you can create a new account, which comes with a year of usage in their Free Tier, at https:/​/​aws.amazon.​com.


During the course of this book, you will need the following tools:

AWS Lambda
AWS RDS
AWS API Gateway
AWS DynamoDB
AWS S3
AWS SQS
AWS Rekognition
AWS Kinesis
AWS SNS


We will learn how to use these tools through the course of this book

## Related Products
* [Vue.js 2 Design Patterns and Best Practices](https://www.packtpub.com/web-development/vuejs-design-patterns-and-best-practices?utm_source=github&utm_medium=repository&utm_campaign=9781788839792)

* [Rust High Performance](https://www.packtpub.com/application-development/rust-high-performance?utm_source=github&utm_medium=repository&utm_campaign=9781788399487)

* [Serverless Programming Solutions [Video]](https://www.packtpub.com/application-development/serverless-programming-solutions-video?utm_source=github&utm_medium=repository&utm_campaign=9781788622325)
