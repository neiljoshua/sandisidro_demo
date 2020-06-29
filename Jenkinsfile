pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'BUILD_SCRIPTS_GIT', branch: 'master')
      }
    }

  }
  environment {
    ENV = 'production'
    BUILD_SCRIPTS_GIT = '\'https://github.com/neiljoshua/sandisidro_demo.git\''
  }
}