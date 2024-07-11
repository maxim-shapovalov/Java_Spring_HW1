# Gradle.<br>
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/gradle-v.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/gradle-build-1.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/gradle-build-2.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/gradle-build-successful.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/build-gradle.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/build-with-dependency-hibernate.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/app.png)
![Gradle1](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/gradle/build-app.png)
# Maven. <br>
![maven](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/maven/package.png).

### pom.xml
```
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.mycompany.app</groupId>
  <artifactId>my-app</artifactId>
  <packaging>jar</packaging>
  <version>1.0-SNAPSHOT</version>
  <name>my-app</name>
  <url>http://maven.apache.org</url>
  <dependencies>
    <dependency>
      <groupId>org.hibernate.orm</groupId>
      <artifactId>hibernate-core</artifactId>
      <version>6.5.2.Final</version>
    </dependency>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>3.8.1</version>
      <scope>test</scope>
    </dependency>
  </dependencies>
</project>
```
![maven](https://github.com/maxim-shapovalov/Java_Spring_HW1/homework/maven/Build_20success.png).
