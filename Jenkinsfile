pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          agent any
          steps {
            sh 'echo "Hello"'
          }
        }

        stage('Build2') {
          steps {
            echo 'Hello2'
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'End'
      }
    }

  }
}