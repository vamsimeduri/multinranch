pipeline {
    agent any

    stages {
        stage('gitclone') {
            steps {
                git branch: 'master', url:'https://github.com/vamsimeduri/multinranch.git'
            }
        }
        stage('echoing the file') {
            steps {
                sh "cat vamsi"
            }
        }
    }
    
    }


