## Use JPA + Hibernate + MySQL in Spring Boot

See here for more informations: 
http://blog.netgloo.com/2014/10/06/spring-boot-data-access-with-jpa-hibernate-and-mysql/

### Usage

http://localhost:7777/create?email=pankajmaurya@gmail.com&name=pankaj
http://localhost:7777/get-by-email?email=pankajmaurya@gmail.com
http://localhost:7777/delete?id=1


### Build and run

#### Configurations

Open the `application.properties` file and set your own configurations for the
database connection.

#### Prerequisites

- Java 7
- Maven 3

#### From terminal

Go on the project's root folder, then type:

    $ mvn spring-boot:run

#### From Eclipse (Spring Tool Suite)

Import as *Existing Maven Project* and run it as *Spring Boot App*.
