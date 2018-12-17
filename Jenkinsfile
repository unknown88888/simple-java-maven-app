pipeline {
  agent {
    docker {
      image 'maven:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'sh \'echo Build\''
        input 'Continue?'
      }
    }
  }
}