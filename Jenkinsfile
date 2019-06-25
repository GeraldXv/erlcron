pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build'
        build 'demo1'
      }
    }
    stage('test') {
      steps {
        input(message: 'need approve', submitter: 'admin')
      }
    }
  }
}