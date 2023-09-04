pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/helloworldbatch17.git', branch: 'master', credentialsId: 'github_credentials')
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Build is successful"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Test successful. welcome"'
      }
    }

  }
}
