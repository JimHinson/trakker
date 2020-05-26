Start mongodb:
mongod

Mongo command line:
mongo

Run tests:
mvn test

Run app:
mvn spring-boot:run

View REST calls:
curl http://localhost:8080

App Help
create data:
curl -i -X POST -H "Content-Type:application/json" -d "{  \"firstName\" : \"Frodo\",  \"lastName\" : \"Baggins\" }" http://localhost:8080/people

mvn test
mvn 