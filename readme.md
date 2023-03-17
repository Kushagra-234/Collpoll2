
 # Readme
 
 
 updated readme 
 
 Added flyway
 
 
 
 added dependency in pom.xml
 
 https://github.com/Kushagra-234/Collpoll2/blob/dev2/pom.xml#L131=L135
 
 
 Added migration folder in 
 src/main/resources/db/migration/v1_init.sql
 https://github.com/Kushagra-234/Collpoll2/blob/dev2/src/main/resources/db/migration/v1_init.sql#L1-L65
 
 added files in postgress properties
 
 https://github.com/Kushagra-234/Collpoll2/blob/dev2/src/main/resources/application-postgres.properties#L1-L8
 
 Added files in application.mysql.properties
 https://github.com/Kushagra-234/Collpoll2/blob/dev2/src/main/resources/application-mysql.properties#L1-L12
 

# Should have java installed in your system 
( preferrably 17 ,less version than 17 of java can show error)

# Install maven in your system 

steps-

 # Clone repo


steps for runnng application

1-./mvnw package

2-./mvnw spring-boot:run -Dspring-boot.run.profiles=mysql

3-java -jar target/*.jar


step 1 to build

step 2 to connect to mysql

step 3 to start


go to localhost:8080


changes to downgrade version of mysql-

changing of version of mysql from 5.8 to 5.7

https://github.com/Kushagra-234/Collpoll2/blob/main/docker-compose.yml#L4-L5


