
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "this is ${env.BUILD_NUMBER}"
            }
        }
        stage('Test') {
            steps {
                echo env.WORKSPACE
            }
        }
        stage('Deploy') {
            steps {
                echo currentBuild.currentResult
            }
        }
    }
}
