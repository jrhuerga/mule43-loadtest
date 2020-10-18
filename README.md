# mule43-loadtest

This project contains artifacts used to load test a Mule 4.3 API.

The source code is under these folders:

* _OAS_ : The API definition in OAS
* _RAML_ : The API definition in RAML
* _Mule_ : The source code of the API. It contains four endpoints: 1) Demonstration of simple JSON object ; 2) Transformation of that JSON object using DataWeave ; 3) Invocation of another endpoint using HTTP ; 4) Invocation via HTTP and DataWeave Transformation
* _Postman_ : Postman collection to test the API. Change the server name and client_id and client_secret
* _JMeter_ : Loadtest invoking the four endpoints. Change the server name and client_id and client_secret




