pipeline {
  agent any
  stages {
    stage('Chrckout') {
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
