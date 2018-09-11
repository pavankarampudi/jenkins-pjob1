pipeline {
  agent any
  stages {
    stage('stage1-DEMO') {
      parallel {
        stage('stage1-DEMO') {
          steps {
            sh 'echo Hello World'
          }
        }
        stage('Stage1-Demo1') {
          steps {
            sh 'echo Hello'
          }
        }
      }
    }
    stage('Stage2-DEMO') {
      steps {
        sh 'echo hello'
      }
    }
  }
}