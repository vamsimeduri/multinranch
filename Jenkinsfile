pipeline {
    agent any

    stages {
        stage('gitclone') {
            steps {
                git branch: 'master', credentialsId: '4f127eb4-bdc8-4ef8-8a8b-c22957b33a13', url: 'https://github.com/vamsimeduri/terraform-module.git'
            }
        }
        stage('echoing the file') {
            steps {
                sh "ls -lrth"
            }
        }
    }
    }
}

