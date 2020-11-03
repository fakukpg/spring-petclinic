pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './gradlew build'
        sh './gradlew jar'
      }
    }

    stage('Test') {
      steps {
        sh './gradlew clean test'
      }
    }

    stage('Validate') {
      steps {
        sh 'ls'
      }
    }

    stage('Deploy') {
      steps {
        sh 'ls'
      }
    }

  }
} 
