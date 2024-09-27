//Funtionality 
    -import CSV file
    -Store data in DB
    -Search that data
    -View data

//Installation of project 
1) composer create-project --prefer-dist laravel/laravel practical_task_demo "7.*" 

2) Changes in env

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=call_details_csv_changes
DB_USERNAME=root
DB_PASSWORD=

//Make Model,Controller,migratiion
1) php artisan make:model

2)php artisan make:controoller

3)php artisan make:migration 

//To start project serve command
 php artisan serve

 //Import CSV
  - Get file
  - Get path
  - use array map for get csv file
  - for remove header from csv and store data use array_shift
  - Fetch data and store into db

//Search
 - For api and view search created single function
 - Make validation for return error if data type is not valid so get fast access to data
 - Also get data if empty return msg that no data exist
 - return data if it exist in db with search

   Note :- We can use boot strap for better UI 

