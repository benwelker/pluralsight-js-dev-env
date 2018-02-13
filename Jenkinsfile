pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Test'
          }
        }
        stage('Test1.1') {
          steps {
            echo 'Test1.1'
          }
        }
      }
    }
  }
}