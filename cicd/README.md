# CI/CD

We're using [Jenkins](http://35.83.54.70:8080/) for automated workflow (pipeline) and [SonarQube](http://35.83.54.70:9000/) for code analysis.

Jenkins and Sonarqube each requires `Jenkinsfile` and `sonar-project.properties` to be included in your repository. These files are specific to the programming language and framework you use. Please see some examples in each folders.

## Setup

Add `Jenkinsfile` and `sonar-project.properties` to the root of your repository.

That's it. The next commit you push will be picked up by Jenkins.
