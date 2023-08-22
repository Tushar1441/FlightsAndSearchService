 # Welcome to Flights Service 

 ## Project Setup 
 - clone the project on your local machine
 - Execute `npm install` on the same path as of your root directory of the downloaded proect
 - Create a `.env` file in the root directory and add the following environment variable
  - `PORT=3000`
- Inside the `src/config` folder create a new file `config.json` and then add the following place of json

```
{
  "development": {
    "username": "YOUR_DB_LOGIN_NAME",
    "password": "YOUR_DB_PASSWORD",
    "database": "FLIGHTS_SEARCH_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
```

- Once you have added your db config as listed above, go to the src folder from your terminal and execute `npm sequelize db:create` 


