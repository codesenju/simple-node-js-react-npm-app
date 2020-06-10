pipeline {
    agent {
        docker {
            image 'codesenju/staging' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
