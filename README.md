# reactiveRates


Run:  
java -jar reactiveTracker-1.0.0-SNAPSHOT-fat.jar -conf conf.json

Server port is 8082.  

Example of GET request  
http://localhost:8082/cryptos/ETH/DASH  


=================== from task description ================

Example of the POST REST endpoint request/response, ETH/DASH pair:  
Request:  
POST /cryptos/  
{  
    "ccy1": "ETH",  
    "ccy2": "DASH"  
}  
Response:  
201 OK  


Example of the GET REST endpoint request/response, ETH/DASH pair:  
Request:  
GET /cryptos/ETH/DASH  
Response:  
{  
    "ratio": 1.345  
}  

