# springboot-aws-sns
Amazon Simple Notification Service Pub/sub messaging for microservices and serverless applications.

SNS is a pub/sub (publisher/subscriber) based technique to pass messages. It could be used to send email/sms to clients directly or we can send a payload to SQS connected to SNS.

SNS supports both A2A and A2P. Application to Application and Application to Person.

Use SNS when you want to publish to multiple subscribers at once. 
Topic - the unique key to which we need to publish which will already be subscribed by many subscribers.
