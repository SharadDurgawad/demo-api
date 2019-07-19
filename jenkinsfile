pipeline {
    agent any

    stages {
    
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        
        stage('Sonar') {
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
