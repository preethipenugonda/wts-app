pipeline {
    agent any

    stages {
        stage('Hello Stage') {
            steps {
                echo 'Hello Gouthami! Jenkins pipeline is working 🎉'
                echo 'welcome to jenkins pipline'
                echo 'Hi i checking for commit event'
                echo ' had your dinner hi  bye'
                echo 'smile'
        
            }
        }
        stage('Terraform') {
            steps {
                
                sh '''
                  terraform init
                  terraform plan
                '''

            }
        }
    }
}
