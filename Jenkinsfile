pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hi'
        sh './mvnw clean compile'
      }
    }

    stage('Unit Test') {
      steps {
        sh './mvnw test'
      }
    }

  }
}