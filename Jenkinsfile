pipeline {
  agent {
    docker {
      image 'centos:8'
      args 'label \'centos8\''
    }

  }
  stages {
    stage('Clone Git Repo') {
      steps {
        sh 'echo Cloning git repository'
      }
    }

    stage('Build') {
      steps {
        sh 'echo Build start here'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo Here start the deployment'
      }
    }

  }
}