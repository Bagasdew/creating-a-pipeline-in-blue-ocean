pipeline {
  agent {
    docker {
      args '-p 46789:3000'
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}