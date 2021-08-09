# CI/CD

We're using [Jenkins](http://35.83.54.70:8080/) for automated workflow (pipeline) and [SonarQube](http://35.83.54.70:9000/) for code analysis.

Jenkins and Sonarqube each requires `Jenkinsfile` and `sonar-project.properties` to be included in your repository. These files are specific to the programming language and framework you use. Please see some examples in each folders.

## Setup

1. Add `Jenkinsfile` and `sonar-project.properties` to the root of your repository.

2. Go to your repository settings, under **Webhooks** menu, click **Add webhook**.

3. Fill `http://35.83.54.70:8080/github-webhook/` for **Payload URL**.

4. Choose `application/json` for **Content type**.

5. Choose `Just the push event` for event that will trigger webhook.

6. Make sure **Active** checkbox is checked.

That's it. The next commit you push will be picked up by Jenkins.
