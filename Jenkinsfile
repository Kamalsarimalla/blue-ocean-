pipeline {
  agent any
  stages {
    stage('installing apache/') {
      steps {
        sh '''pipeline {
    agent any
    stages {
        stage (\'install apache2\'){
            steps{
                sh (\'sudo apt-get update && sudo apt install -y apache2\')
            }
        }
    }'''
        }
      }

    }
  }