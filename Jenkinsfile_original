pipeline {
    agent any
    
    
    
    stages {
        stage ('Checkout') {
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'GITHUB_credentials', url: 'https://github.com/sachkale/Maven_Project.git']]])
                }
        }
        
       
       stage ('Build') {
            steps{
                echo "This is stage 1"
                }
        }
       
            stage('Test') {
            steps {
                echo "This is stage 2"
                
            }
        }
    }
}
