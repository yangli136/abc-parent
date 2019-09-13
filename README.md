# abc-parent
This is parent pom for Spring Boot based application. The pom uses spring-boot-dependencies to control dependencies in order to reduce dependency related maintenance effort. The intention is that all applications will go and update along  with Spring Boot latest versions and we only define the versions that are required to be overridden here.

# Maven Parent POM for a Spring Boot based application


Spring Boot based Java application is a good choice for new Java applications. The Spring Boot eco-system provides numerous libraries and tools.

In order to better manage the versions of huge amount of libraries, it is a good approach to upgrade the libraries along with Spring Boot upgrades. It will save huge maintenance and integration effort by taking advantage of the work Spring Boot team has already done.

The following sample parent POM provides the following customized features:

1. removed the Logback and Appache Commons Logging related dependencies
1. added unit test dependencies
1. enabled resource filtering
1. configured Google stype check
