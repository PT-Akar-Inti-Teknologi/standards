# CI/CD

We're using [Jenkins](https://jenkins.akarinti.tech/) for automated workflow (pipeline) and [SonarQube](https://sonar.akarinti.tech/) for code analysis.

Jenkins and Sonarqube each requires `Jenkinsfile` and `sonar-project.properties` to be included in your repository. These files are specific to the programming language and framework you use. Please see some examples in each folders.

## Setup

Add `Jenkinsfile` and `sonar-project.properties` to the root of your repository.

That's it. The next commit you push will be picked up by Jenkins.
