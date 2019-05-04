$mvn clean package
$java -jar ./target/spring-boot-admin-0.0.1-SNAPSHOT.jar


$docker image build -t admin .
$docker container run -d --name admin -p 8080:8080 admin