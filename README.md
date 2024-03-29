# employee_registry_backend[![Build Status](https://dev.azure.com/chandra-prakash-reddy/EmployeeRegistry/_apis/build/status/chandra-prakash-reddy.employee_registry_backend%20(1)?branchName=master)](https://dev.azure.com/chandra-prakash-reddy/EmployeeRegistry/_build/latest?definitionId=6&branchName=master) [![Maven Central](https://img.shields.io/maven-central/v/com.github.chandra-prakash-reddy/employee-registry.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22com.github.chandra-prakash-reddy%22%20AND%20a:%22employee-registry%22)


SpringBoot Application which  performs CRUD operations on employee registry data

# prerequisites # 
   * Install Java8
      * installation  : https://www.oracle.com/technetwork/java/jdk8-downloads-2133151.html
      * documentation : https://docs.oracle.com/javase/8/docs/api
   * SpringBoot sources
      * documentaion : https://spring.io/docs
   * Maven
      * installation  : https://maven.apache.org/download.cgi
      * documentation : https://maven.apache.org/guides


# Run #
   * move to project root directory
   * run ***mvn verify*** 
   * run ***java -jar target/employee-registry --server.port=<port\>***
      * example: java -jar target/employee-registry.jar --server.port=7878
  
  # Docker Run #
   * ***docker run command :***
      * ***docker run -p \<port>:8080 --name <container_name> chandraprakashreddy/applications:employee-registry-services-v1.01***
  
   * ***run arguments :***
      * \<port> : provide the port number on which it should be run the process
      * <container_name> : provide the container name
# verify #
   * open ***http://\<host>:\<port>/swagger-ui.html***
      * ***example:- http://localhost:7878/swagger-ui.html*** can see sevice running
# pom.xml #
   Find the pom dependency reference here [pom.xml](https://search.maven.org/artifact/com.github.chandra-prakash-reddy/employee-registry/1.1/jar "pom.xml")

# License #
   This project is licensed under the MIT License - see the [License](https://opensource.org/licenses/MIT "License")  for details
