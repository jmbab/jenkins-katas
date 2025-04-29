pipeline {
  agent any
  stages {
    stage('Hello-World') {
      parallel {
        stage('Hello-World') {
          steps {
            sh 'echo "Hello World!"'
          }
        }

        stage('Build') {
          steps {
            sh 'ci/build-app.sh'
          }
        }

      }
    }

  }
}