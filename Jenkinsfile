pipeline {
  agent any
  stages {
    stage('build') {
      steps {
          docker.image('php').inside {
              sh "php -version"
          }
      }
    }
  }
}