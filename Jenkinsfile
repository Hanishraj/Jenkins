pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is  Build stage'
      }
    }

    stage('Test') {
      steps {
        echo 'This is Test'
      }
    }

    stage('Approval') {
      steps {
        input 'you want to continue'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }

  }
}