pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker --version'
      }
    }

    stage('Test1') {
      steps {
        sh 'echo \'Welcome home\''
      }
      steps {
        sh 'echo \'Welcome home2\''
      }
    }
  }
}
