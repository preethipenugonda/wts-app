pipeline {
    agent any

    stages {
        stage('Hello Stage') {
            steps {
                echo 'Hello Gouthami! Jenkins pipeline is working 🎉'
                echo 'welcome to jenkins pipline'
                echo 'Hi i checking for commit event'
        
            }
        }
        stage('Terraform') {
            steps {
                terraform init
                terraform plan
                
            }
        }
    }
}
