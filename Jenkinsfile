pipeline {
  agent {
    docker {
      image 'maven:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo Build'
        input 'Continue?'
      }
    }
  }
}