pipeline {
  agent {
    docker {
      args '-p 3001:3001'
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install '
      }
    }
  }
}