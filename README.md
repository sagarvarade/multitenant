# multitenant
This is to connect to multiple dbs in one spring application <br>
With help of below link : <br>
https://github.com/sumanentc/multitenant   <br>
https://github.com/sunitk/multitenancy-dynamic-tenant <br>
https://medium.com/@paulushc/multi-database-application-with-spring-boot-777aaf5a1e4e   <br>
https://medium.com/@joeclever/using-multiple-datasources-with-spring-boot-and-spring-data-6430b00c02e7  <br>

********************************************************************************************************

THIS IS SIMPLY A SPRING APPLLICATION WHICH CAN CONNECT WITH MULTIPLE SCHEMAS AT ONE TIME

<b>This will work only with Mysql Databse <br>
<b>This does not contain any Security related stuff ,above links can be expolered as per requirement <br>
  
  
Pre requsites :
1. Spring
2. Java
3. MYSQL installed

  
End points for basic check
  
 1. http://localhost:8080/user/test1
  
 2. http://localhost:8080/tencheck With Headers as below  <br>
  Content-Type : application/json  <br>
  tenantId     : test1            <br>
  
  
Databases 
  
1. Public 
2. test1
3. test2
4. test3
 
  
Public Schema have configuration as belew for each schema that can be used in this Application: <br>
|_. id |_. password |_. tenantId |_. url |_. username |_. version | <br>
| 1 | sagar | test1 | jdbc:mysql://192.168.1.100:3306/test1 | sagar | 0 |<br>
| 2 | sagar | test2 | jdbc:mysql://192.168.1.100:3306/test2 | sagar | 0 |<br>
| 3 | sagar | test3 | jdbc:mysql://192.168.1.100:3306/test3 | sagar | 0 |<br>
  




