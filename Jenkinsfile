pipeline {
  agent any
  stages {
    stage('sonarscan') {
      steps {
        git(url: 'https://github.com/jadelinlin/learngit01', branch: 'master')
      }
    }
    stage('test') {
      steps {
        sleep 10
      }
    }
  }
}