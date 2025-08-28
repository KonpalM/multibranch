@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Build & Push Docker Image') {
            steps {
                script {
                    dockerBuildAndPush(
                        image: "kmaharwal1/jenkins-shared-library-testapp",
                        tag: "1.0.0",
                        registry: "docker.io"
                    )
                }
            }
        }
    }
}
