pipeline {
  agent any
  stages {
    stage('CheckoutCode') {
      steps {
        git(url: 'https://github.com/waladevops/checkpointjenkins', branch: 'main')
      }
    }

  }
}