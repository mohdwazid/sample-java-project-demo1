pipeline {
  agent {
    node {
      label 'centos8'
    }

  }
  stages {
    stage('Clone Git Repo') {
      steps {
        sh 'sh "echo cloning git repository"'
      }
    }

    stage('Build') {
      steps {
        sh 'sh "echo Build start here"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'sh "echo Here start the deployment"'
      }
    }

  }
}