pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        git(url: 'https://github.com/vargantianuradha/flyhighproject.git', branch: 'master')
      }
    }

  }
  environment {
    stage = 'build'
  }
}