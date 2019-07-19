pipeline {
    agent any

    stages {
    
        stage('Checkout Source code') {
            steps {
                echo 'Chekcking out source code..'
            }
        }
        
        stage('Build Source') {
            steps {
                echo 'Building source code..'
            }
        }
        
        stage('Sonar Analysis') {
            steps {
                echo 'Sonar Code Coverage..'
            }
        }
        
        stage('Build Image') {
            steps {
                echo 'Building Docker Image..'
            }
        }
        
        stage('Push Image') {
            steps {
                echo 'Pushing Docker Image..'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying Container....'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing Application..'
            }
        }
        
    }
}
