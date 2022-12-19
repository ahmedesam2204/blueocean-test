pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is Build stage'
      }
    }

    stage('Test') {
      steps {
        echo 'This is Test'
      }
    }

    stage('Deploy') {
      steps {
        input(message: 'Are you sure deploy?', ok: 'Yes,I`m sure')
        echo 'This is Deploy stage'
      }
    }

  }
}