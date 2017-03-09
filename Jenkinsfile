pipeline {
  agent any
  stages {
    stage('build') {
      steps {
node {
        stage "Prepare environment"
          docker.image('php').inside {
            stage "Checkout and build deps"
                sh "php -version"
          }
}
    }
  }
}
}