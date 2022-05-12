# multitenant
This is to connect to multiple dbs in one spring application 
With help of below link :
https://github.com/sumanentc/multitenant
https://github.com/sunitk/multitenancy-dynamic-tenant
https://medium.com/@paulushc/multi-database-application-with-spring-boot-777aaf5a1e4e
https://medium.com/@joeclever/using-multiple-datasources-with-spring-boot-and-spring-data-6430b00c02e7

********************************************************************************************************

THIS IS SIMPLY A SPRING APPLLICATION WHICH CAN CONNECT WITH MULTIPLE SCHEMAS AT ONE TIME

<b>This will work only with Mysql Databse <br>
  
  
Pre requsites :
1. Spring
2. Java
3. MYSQL installed

  
End points for basic check
  
 1. http://localhost:8080/user/test1
  
 2. http://localhost:8080/tencheck With Headers as below 
  Content-Type : application/json
  tenantId     : test1
  
  
Databases 
  
1. Public 
2. test1
3. test2
4. test3
 
  
  

