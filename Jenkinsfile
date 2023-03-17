pipeline {
  agent any
  stages {
    stage('Chectkou') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/Hello-World.git', branch: 'master', credentialsId: 'github_cred')
      }
    }

  }
}