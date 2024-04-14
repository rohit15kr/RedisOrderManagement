to run the file just 

step 1:
 npm i 

 step 2 : 
 nodemon serve.js

check for api 
step 1:
 go to postman or thunderclient and create a post request to this api 

http://localhost:3005/api/client/

then add a body as request in json data sample data for both client info (1121 msgType) is 

{
    "MsgType": 1121,
    "OperationType": 100,
    "TenantId":1,
    "OMSId":1,
    "ClientId":8,
    "ClientName":" Client 1",
    "Remark": 6633
}

sample data for both  order info (1120 msgType) is 
{
    "MsgType": 1120,
    "OperationType": 100,
    "TenantId":1,
    "OMSId":1,
    "ClientId":9,
    "OrderType":"1",
    "OrderId":3,
    "Token":7
}
