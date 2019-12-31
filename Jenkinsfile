pipeline {
  agent any
  stages {
    stage('Job1') {
      parallel {
        stage('Job1') {
          steps {
            bat 'echo "a"'
          }
        }

        stage('Job2') {
          steps {
            bat 'echo "a"'
          }
        }

        stage('Job3') {
          steps {
            bat 'echo a'
          }
        }

      }
    }

  }
}