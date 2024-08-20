pipeline {
    agent any

    stages {
        stage('CheckOut') {
            steps {
                echo 'CheckOut'
            }
        }
    

    
    stage('Build') {
            steps {
                echo 'Build Success'
            }
        }
        
        
    stage('Unit Test') {
            steps {
                echo 'Test Success'
            }
        }
        
    stage('Code Scan') {
            steps {
                echo 'Scan Success'
            }
        }
        
    stage('Docker') {
            steps {
                echo 'Image Scan/Build/Push Success'
            }
        }
    }
}
