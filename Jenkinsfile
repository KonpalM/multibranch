@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Test Shared Library') {
            steps {
                script {
                    helloWorld('from main')
                }
            }
        }
    }
}
