pipeline {
  agent any
  stages {
    stage('Install NPM') {
      steps {
        sh 'apt update && apt install -y npm'
      }
    }

    stage('Start Init NPM') {
      steps {
        sh 'npm install'
      }
    }

  }
}