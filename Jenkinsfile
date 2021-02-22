pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'node --version'
          }
        }

        stage('Docker') {
          steps {
            sh 'docker --version'
          }
        }

      }
    }

    stage('error') {
      steps {
        sh 'docker build -t image1 .'
      }
    }

  }
}