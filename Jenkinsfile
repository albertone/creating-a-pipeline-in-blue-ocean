pipeline {
  agent {
    node {
      label 'jenkins_agent'
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