pipeline {
  agent any
  stages {
    stage('First') {
      parallel {
        stage('First') {
          steps {
            echo 'I am first stage'
          }
        }
        stage('Parallel') {
          steps {
            echo 'I am second stage'
          }
        }
      }
    }
    stage('Post') {
      steps {
        echo 'post stage is called'
      }
    }
  }
}