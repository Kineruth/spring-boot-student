# Spring Boot - Project

This application sets up a "student" database, adds students to the table and posts them in a JSON format on an HTTP localhost web page.    

#### **Technologies used:**  
Spring Boot, Postman, Spring Web, Spring Data JPA, PostgreSQL, SQL shell, IntelliJ.  

PostgreSQL - for creating a rational database.  
Postman - for testing the client side, sending Get/Post/Put/Delete requests and viewing the responses: 


#### **How To Run The Project:**  
* Clone the project: https://github.com/Kineruth/spring-boot-project.git .  
* Connect to "student" database using ```\c student``` on SQL Shell:   
* Run the application on your IDE.  
* Go to (URL) http://localhost:8080/api/v1/student on your web browser.  

![localhost](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/web.PNG)   
* Using Postman - running some requests.  
1. Get request:  
![Get req](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/get.PNG)  
2. Post request:  
![Post req](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/post.PNG)  
3. Post response:  
![Post res](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/post2.PNG)  
4. Put request:  
![Put req](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/put.PNG)  
5. Put response:  
![Put res](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/put2.PNG)  
6. Delete request:  
![Delete req](https://github.com/Kineruth/spring-boot-project/blob/master/springboot-project/src/main/resources/pictures/delete.PNG)   




#### **Student Entity fields:**
* Id (primary key) - generated by @SequenceGenerator starting from 1.  
* Name - is given as an input.  
* Email - is given as an input. 
* Date of birth -is given as an input.  
* Age - generated by @Transient.






