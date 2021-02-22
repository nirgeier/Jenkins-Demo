pipeline {
  agent {
    docker {
      image 'node'
    }

  }
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

    stage('Dummy') {
      steps {
        sh 'docker build -t image1 .'
      }
    }

  }
}