# Serverless Udemy Facebook Chatbot Lambda Function

This lambda function is used to define a specific Lex handler, used to manage udemy courses suggestions, due to specific group messages for each opted-in in user.

Functions provides :
* Lex preconditions for incoming messages
* Lex feature announce
* Lex opt-in the bot
* Lex opt-out the bot
* On-flight message decomposition in keywords
* Store on DynamoDB of keywords and relative count per user
* Enquire to specific Udemy courses
* User private presentation of suggested courses based on his preferences


### Goals ###

N.D.


### Parameters ###

N.D.


### Install ###

To install function use following command :
```bash
  sls deploy
  or
  serverless deploy
```

If you want to test locally :
```bash
  npm install
```
Then install Kubeless and Serverless frameworks at :

[Serverless](https://serverless.com/) with all preconditions.

[Kubeless](https://github.com/kubeless/kubeless) with all preconditions.


### Usage ###

N.D.


### License ###

[Customized LGPL](/LICENSE)
