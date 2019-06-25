pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build'
      }
    }
    stage('test') {
      steps {
        input(message: 'need approve', submitter: 'admin')
      }
    }
  }
}