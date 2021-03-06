pipeline {
  agent any
  stages {
    stage('Test1') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Directory listing') {
      steps {
        bat(returnStdout: true, script: 'dir', returnStatus: true)
      }
    }

  }
  environment {
    Laptop = 'MC-DELL'
  }
}