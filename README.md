# SpringBootRestApiValidations
This project is built to explain the CRUD operations using SpringBoot Rest API and also we have performed validations for entity fields of database table. 
Use the below URLs to perform CRUD Operations,

i) Post-> Create Entry-- Use POST end point
	localhost:9393/api/shop/signup
	Body Payload:
{
"itemName": "bell",
"gst": "22",
"itemPrice": "4668",
"expdate": "23-04-2026"
}

ii) GetAll-Use GET endpoint
     Get all -> localhost:9393/api/mypage/fetchAll

iii)GET user details by id-Use GET Endpoint
    localhost:9393/api/mypage/1

iv)Update user details if id exists->Use PUT endpoint
   localhost:9393/api/mypage/1

v)Delete user details using userId->Use DELETE endpoint
   localhost:9393/api/mypage/1

Swagger-ui:
http://localhost:9393/swagger-ui.html
