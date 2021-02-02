pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'GitHubCreds', url: 'https://github.com/kirandvn/JenkinsPipelineDemo'
            }
        }
    }
}
