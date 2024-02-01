pipeline {
    agent any
    stages {
        stage('Checkout code') {
             steps {
                checkout scm
      }
        }
        stage('Install packages'){
            steps  {
                 sh 'npm install'
            }
        }
    }
}
