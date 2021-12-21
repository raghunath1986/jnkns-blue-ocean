pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Fluffy Build'
        sh 'echo Another Placeholder !'
      }
    }

    stage('Fluffy Test') {
      steps {
        sh 'sleep 5'
        sh 'echo success!'
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'Fluffy Deploy'
      }
    }

  }
}