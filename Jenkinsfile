pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "npm evn go 增加了docker权限 ! "; npm install'
            }
        }
        
    }
}