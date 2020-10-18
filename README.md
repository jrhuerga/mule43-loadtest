# mule43-loadtest

This project contains artifacts used to load test a Mule 4.3 API.

The source code is under these folders:

* _OAS_ : The API definition in OAS
* _RAML_ : The API definition in RAML
* _Mule_ : The source code of the API. It contains four endpoints: 1) Demonstration of simple JSON object ; 2) Transformation of that JSON object using DataWeave ; 3) Invocation of another endpoint using HTTP ; 4) Invocation via HTTP and DataWeave Transformation
* _Postman_ : Postman collection to test the API. Change the server name and client_id and client_secret
* _JMeter_ : Loadtest invoking the four endpoints. Change the server name and client_id and client_secret

You can deploy the API in MuleSoft Anypoint (CloudHub) creating a free account in https://anypoint.mulesoft.com/

Once you have deployed the API in CloudHub and created an API instance, you will need to modify the properties of the Mule project, Postmand and JMeter to reflect the address of your server, and the client ID and secret.


