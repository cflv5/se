# To Run
First, build project with maven  
`mvn clean install -X -U`  

Then, set SE_KEYSTORE_PASS environemnt variable with the keystore's password  
For Unix system:  
`export SE_KEYSTORE_PASS=ytucese`  
`docker-compose up --build`  
  
Then app is at: http://localhost:8083/

Go to the address http://localhost:8083/register to create account.
Then http://localhost:8083/login to login to the app.
