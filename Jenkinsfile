pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        bat 'npm install'
        bat 'npm run test_task'
      }
    }

  }
}