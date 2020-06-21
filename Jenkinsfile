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

        stage('Unit Test') {
          steps {
            echo 'Unit Test'
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