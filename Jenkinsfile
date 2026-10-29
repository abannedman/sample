pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh 'run clean package'
            }
        }

        stage('Test') {
            steps {
                sh 'run mvn test'
            }
        }
    }
}
