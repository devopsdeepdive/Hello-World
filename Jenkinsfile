pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/Hello-World.git', branch: 'master', credentialsId: 'github_cred')
      }
    }

    stage('Build') {
      steps {
        echo 'Build is successful'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing is successful'
      }
    }

  }
}