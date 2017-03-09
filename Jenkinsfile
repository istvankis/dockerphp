node {
  stage 'Building image'
  def phpApp = docker.image('php')
  phpApp.pull()

  stage 'Test image'

  phpApp.inside {
    php -version
  }
}
