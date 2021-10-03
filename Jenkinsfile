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
            sh 'echo \'Welcome\''
          }
        }

        stage('Test2') {
          steps {
            sh 'echo Welcome3333'
          }
        }

      }
    }

    stage('Test33') {
      steps {
        echo 'test'
        sh 'echo \'Welcome2\''
      }
    }

  }
}