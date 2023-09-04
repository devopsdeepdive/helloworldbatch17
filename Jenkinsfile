pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/helloworldbatch17.git', branch: 'master', credentialsId: 'github_credentials')
      }
    }

  }
}