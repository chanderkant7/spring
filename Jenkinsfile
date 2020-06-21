pipeline {
  agent any
  stages {
    stage('Checkout') {
      parallel {
        stage('Checkout') {
          steps {
            echo 'Checking code from Git'
          }
        }

        stage('test') {
          steps {
            echo 'unit test'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Doing the Maven Build'
      }
    }

    stage('Docker') {
      steps {
        echo 'Creating dockerfile'
      }
    }

  }
}