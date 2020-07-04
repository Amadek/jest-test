pipeline {
  agent { dockerfile true }
  stages {
    stage('Test') {
      steps {
        sh 'ls -a'
        sh 'npm test'
      }
    }
  }
}
