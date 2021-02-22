pipeline {
  agent none
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

    stage('') {
      steps {
        sh 'docker build -t image1 .'
      }
    }

  }
}