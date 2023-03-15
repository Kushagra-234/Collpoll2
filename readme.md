
Readme

# should have java installed in your system 
(less version than 17 of java can show error)

#install maven in your system 

clone repo


steps
1-./mvnw package
2-./mvnw spring-boot:run -Dspring-boot.run.profiles=mysql
3-java -jar target/*.jar


step 1 to build
step 2 to connect to mysql
step 3 to start

go to localhost:8080


changes to downgrade version of mysql-

changing of version of mysql from 5.8 to 5.6

https://github.com/Kushagra-234/Collpoll2/blob/main/docker-compose.yml#L4-L5


