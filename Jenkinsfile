pipeline {
    agent any
    stages {
        stage('Checkout code') {
             steps {
                checkout scm
      }
        }
        stage('Install and build'){
            steps  {
                 sh 'npm install'
                 sh 'npm build' 
            }
        }
    }
}
