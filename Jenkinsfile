pipeline {
  agent {
    docker {
      image 'php:7.2-fpm'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'Hello'
      }
    }
  }
  environment {
    APP_VERSION = '1.0.0'
  }
}