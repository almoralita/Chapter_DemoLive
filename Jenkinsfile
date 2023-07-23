pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'hello'
      }
    }

    stage('Testing A') {
      parallel {
        stage('Testing A') {
          steps {
            echo 'byee'
          }
        }

        stage('Testing B') {
          steps {
            sh '''sleep 10
echo done'''
          }
        }

      }
    }

  }
}