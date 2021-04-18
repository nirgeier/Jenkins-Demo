pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker --version'
      }
    }

    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            sh 'echo \'Welcome home\''
          }
        }

        stage('Test2') {
          steps {
            sh 'echo 3'
          }
        }

      }
    }

  }
}