# Springboot-test

JAVA 17

-mvn clean install

-mvn install

-mvn test

-mvn verify

-mvn site

# Spring boot starter test

	   <dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>


# Maven surfire report


# Jacoco report


# Actuator 
        "self": {
            "href": "http://localhost:9090/actuator",
            "templated": false
        },
        "beans": {
            "href": "http://localhost:9090/actuator/beans",
            "templated": false
        },
        "caches-cache": {
            "href": "http://localhost:9090/actuator/caches/{cache}",
            "templated": true
        },
        "caches": {
            "href": "http://localhost:9090/actuator/caches",
            "templated": false
        },
        "health-path": {
            "href": "http://localhost:9090/actuator/health/{*path}",
            "templated": true
        },
        "health": {
            "href": "http://localhost:9090/actuator/health",
            "templated": false
        },
        "info": {
            "href": "http://localhost:9090/actuator/info",
            "templated": false
        },
        "conditions": {
            "href": "http://localhost:9090/actuator/conditions",
            "templated": false
        },
        "configprops-prefix": {
            "href": "http://localhost:9090/actuator/configprops/{prefix}",
            "templated": true
        },
        "configprops": {
            "href": "http://localhost:9090/actuator/configprops",
            "templated": false
        },
        "env": {
            "href": "http://localhost:9090/actuator/env",
            "templated": false
        },
        "env-toMatch": {
            "href": "http://localhost:9090/actuator/env/{toMatch}",
            "templated": true
        },
        "loggers": {
            "href": "http://localhost:9090/actuator/loggers",
            "templated": false
        },
        "loggers-name": {
            "href": "http://localhost:9090/actuator/loggers/{name}",
            "templated": true
        },
        "heapdump": {
            "href": "http://localhost:9090/actuator/heapdump",
            "templated": false
        },
        "threaddump": {
            "href": "http://localhost:9090/actuator/threaddump",
            "templated": false
        },
        "metrics-requiredMetricName": {
            "href": "http://localhost:9090/actuator/metrics/{requiredMetricName}",
            "templated": true
        },
        "metrics": {
            "href": "http://localhost:9090/actuator/metrics",
            "templated": false
        },
        "scheduledtasks": {
            "href": "http://localhost:9090/actuator/scheduledtasks",
            "templated": false
        },
        "mappings": {
            "href": "http://localhost:9090/actuator/mappings",
            "templated": false
        }

# Spring logging
