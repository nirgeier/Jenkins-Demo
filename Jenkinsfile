pipeline {
  agent {
    docker {
      image 'node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'Welcome\''
      }
    }

    stage('Pack') {
      steps {
        sh 'docker build .'
        sh 'docker build .'
      }
    }

    stage('Pack2') {
      steps {
        sh 'docker build -t image1 .'
      }
    }

  }
}
