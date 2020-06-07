pipeline {
  agent any
  stages {
    stage('Checkout Dev') {
      steps {
        echo 'Checking code from Git'
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
