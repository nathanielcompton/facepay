# Facepay
### Facial recognition  for payment processing

Created during a 48-hour financial technology hackathon for the [Advanced Technology Development Center](http://atdc.org/) at Georgia Tech, Facepay is an attempt to provide real-world financial transactions without the need of a physical payment device (cash, credit cards, mobile payment systems.)

**_Technical Summary_**

Facepay leverages the [Microsoft Face API](https://azure.microsoft.com/en-us/services/cognitive-services/face/) to detect faces and compare them against users in the Facepay database. Registered users in Facepay's database each have a set of portrait images for the Face API to compare against, as well as a tokenized credit card on file to use with the [Worldpay Digital Payment System](https://developer.worldpay.com/). Practically, a camera records a picture of a user, checks the Facepay database for a match, and calls the tokenized credit card for processing an electronic transaction.

**_Future TODO:_**
* Port Facepay to React Native for running on mobile devices
* Create configuration files to store constants, token information, and endpoint environment information
* Finish online portal for users to view and edit account preferences and transactional data
* Unit and integration testing
