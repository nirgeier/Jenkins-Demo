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
      agent {
        docker {
          image 'node'
        }

      }
      steps {
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