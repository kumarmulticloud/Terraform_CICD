pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/CloudTechDevOps/Terraform_CICD.git'
            }
        }
        stage('Init') {
            steps {
                sh 'terraform init'
            }
        }
    }
}
