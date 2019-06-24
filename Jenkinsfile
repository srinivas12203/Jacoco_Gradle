pipeline {
  agent any
  stages {
    stage('clean') {
      steps {
        bat(script: 'gradle clean', label: 'for cleaning Gradle')
      }
    }
    stage('build') {
      steps {
        bat(script: 'gradle build', label: 'for building')
      }
    }
    stage('test') {
      steps {
        bat(script: 'gradle test', label: 'for testing')
      }
    }
  }
}