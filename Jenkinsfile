pipeline {
    agent any

    stages {
        stage('gitclone') {
            steps {
                git branch: 'master', url: 'https://github.com/vamsimeduri/terraform-module.git'
            }
        }
        stage('echoing the file') {
            steps {
                sh "ls -lrth"
            }
        }
    }
    
    }


