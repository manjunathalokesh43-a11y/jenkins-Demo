pipeline {

    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/manjunathalokesh43-a11y/jenkins-Demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
