pipeline {
  agent any
  stages {
    stage('pull') {
               steps {
            git(url: 'https://github.com/vargantianuradha/flyhighproject.git', branch: 'master')
          }
        }

        stage('build') {
          steps {
            echo 'inside build'
             sh `./build.sh`
          }
        }
  }
  environment {
    stage = 'build'
  }
}
