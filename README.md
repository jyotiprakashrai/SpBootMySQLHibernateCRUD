# SpBootMySQLHibernateCRUD
Demo to create RESTful Web Service to perform CRUD operations using Spring Boot with MySql database. Implementation of HTTP methods GET, PUT, DELETE and POST.
###########################################################################################
###########################################################################################

1. To Add employee details

  -http://localhost:8080/rest/employee/
  
  -select POST method
  
  -In Headers set "Content-Type" application/json
  
  -In Body select raw type and put
     {
      "firstname": " ",
      "lastname": " ",
      "designation": " ",
      "salary": 
      }
      
 2. To get list of all Employees
 
   -http://localhost:8080/rest/employee/
   -select GET method
   
 3. To get single employee with given id
 
    -http://localhost:8080/rest/employee/{id}
    -select GET method
    
 4. To delete single employee with given id
     
     -http://localhost:8080/rest/employee/{id}
     -select DELETE method
     
 5.  To Update an existing employee details

  -http://localhost:8080/rest/employee/
  
  -select PUT method
  
  -In Headers set "Content-Type" application/json
  
  -In Body select raw type and put updated details
     {
      "firstname": " ",
      "lastname": " ",
      "designation": " ",
      "salary": 
      }
