pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/Hello-World.git', branch: 'master', credentialsId: 'github_cred')
      }
    }

  }
}