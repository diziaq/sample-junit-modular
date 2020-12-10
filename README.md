This project is a sample for demonstration of JUnit 5 testing of a java module.

### Prerequisites
1. have `main/java/module-info.java` with the module definition
2. use JUnit 5.7.0
3. use `maven-surefire-plugin:3.0.0+`


### Problem description

###### Invoke `mvn test` to run tests.

- Test **runs as expected** when `SampleTest` class and `SampleTest.test` method are both `public`.
- Test **fails to start** when either class or method is not `public`
(although generally JUnit 5 allows omitting the modifier)

---

See related question https://stackoverflow.com/questions/65218523
