pipeline {
   agent { docker { image 'node:22.14.0-alpine3.21' } }
  stages {
    stage('Tests') {
      steps {
        bat 'npm install'
        bat 'npm run wdio'
      }
      
    }
  }
}