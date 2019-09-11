pipeline {
  agent {
    docker {
      args '-p 46789:3000'
      image 'node:10'
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