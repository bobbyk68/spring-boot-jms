# spring-boot-jms
Setting up JMS with Spring Boot


uses activemq and mongodb ; throws a transaction rollback ( use docker for activemq ) and embedded mongodb

        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-data-mongodb</artifactId>
        </dependency>
        <dependency>
            <groupId>de.flapdoodle.embed</groupId>
            <artifactId>de.flapdoodle.embed.mongo</artifactId>
        </dependency>


