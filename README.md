# Command to run sonarqube analysis
```
mvn clean verify sonar:sonar \
    -Dsonar.login=XXXXX \
    -Dsonar.host.url=https://sonarcloud.io \
    -Dsonar.organization=meyy-innerpeace \
    -Dsonar.projectKey=maven-sonar
```
# Reference Links

- https://docs.sonarcloud.io/advanced-setup/ci-based-analysis/sonarscanner-for-maven/
- https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/
- https://github.com/SonarSource/sonar-scanning-examples/tree/master/sonarqube-scanner-maven/maven-basic
