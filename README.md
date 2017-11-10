# POSTMAN COLLECTION FOR TESTING IYZIPAY API

The easiest way of learning iyzipay API is testing the web endpoints by using Postman or SoapUI. We created a set of configurations on Postman. You can import the collection file in this project in you local Postman or SoapUI application and start using.

The tests will run on **Sandbox environment**.

## HOW TO START

First, you need api key and secret key. In order to get these values, complete the following steps:
* Register from [merchant registration page of Sandbox](https://sandbox-merchant.iyzipay.com/register)
* Open [settings page](https://sandbox-merchant.iyzipay.com/register)
* Click on API Key and Secret Key boxes to see and copy the required values
* Copy these values. You will need to paste them in Postman.

Then open Postman and follow these steps:
* Import [iyzipay API collection file](https://raw.githubusercontent.com/kahramani/iyzipay-postman/master/iyzipay.postman_collection.json) in postman
* Click on eye icon on the right top of Postman UI. [Paste baseUrl, apiKey and secretKey values to related fields](https://raw.githubusercontent.com/kahramani/iyzipay-postman/master/iyzipay-postman_environment.png).

Now you can continue using Postman for testing iyzipay API.

## HOW TO AUTOMATE API TESTING

The best way of automating API testing is using Postman, Newman and Jenkins. You can check the details from [How to write powerful automated API tests with Postman, Newman and Jenkins](http://blog.getpostman.com/2015/09/03/how-to-write-powerful-automated-api-tests-with-postman-newman-and-jenkins/)

## USING SOAPUI 

You can also use SoapUI for running the tests. You can check the details from [Importing SoapUI projects into Postman](http://blog.getpostman.com/2016/04/27/importing-soapui-projects-into-postman/)

## CREDITS

These tests are originally developed by Kurtuluş Şahin from iyzico.
