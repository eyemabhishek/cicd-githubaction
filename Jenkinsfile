pipeline {
    agent any
    
    stages {
        stage('Checkout code ') {
             steps {
                checkout scm
      }
        }

        stage('Install Dependencies'){
            sh 'npm install'
        }

   
    }
}
