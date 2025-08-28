@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Build & Push Docker Image') {
            steps {
                script {
                    dockerBuildAndPush(
                        image: "myteam/myapp",
                        tag: "1.0.0",
                        registry: "my-docker-registry.com"
                    )
                }
            }
        }
    }
}
