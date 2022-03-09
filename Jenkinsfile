pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                sh './mvnw clean test -e'
            }
        }

        stage('Compile') {
            steps {
                sh './mvnw clean compile -e'
            }
        }

        stage('Test') {
            steps {
                sh './mvnw clean test -e'
            }
        }
    }
}
