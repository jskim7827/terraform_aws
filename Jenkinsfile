pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "j"
if'''
      }
    }
    stage('Unit Test') {
      steps {
        pwd(tmp: true)
      }
    }
    stage('Deploy') {
      steps {
        git(url: 'http://git.com', branch: 'master')
      }
    }
  }
}