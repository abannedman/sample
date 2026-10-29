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
                sh 'echo "Start build..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Start mvn test..."'
            }
        }
    }
}
