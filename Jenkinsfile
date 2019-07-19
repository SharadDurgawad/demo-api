pipeline {
    agent any

    stages {
    
        stage('Build Source') {
            steps {
                echo 'Building..'
            }
        }
        
        stage('Sonar Analysis') {
            steps {
                echo 'Sonar Code Coverage..'
            }
        }
        
        stage('Build Image') {
            steps {
                echo 'Build Docker Image..'
            }
        }
        
        stage('Push Image') {
            steps {
                echo 'Push Docker Image..'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        
    }
}
