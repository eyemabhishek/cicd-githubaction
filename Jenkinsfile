pipeline {
    agent any
    
    stages {
        stage('Checkout code ') {
             steps {
                checkout scm
      }
        }

        stage('Install and build'){
            sh 'npm install'
            sh 'npm build'
        }

   
    }
}
