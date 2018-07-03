pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checking Out..'
            }
        }    
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
