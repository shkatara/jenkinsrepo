pipeline {
  agent {
    node {
      label 'test'
    }
    
  }
  stages {
    stage('build stage') {
      steps {
        git(url: 'https://github.com/shkatara/jenkinsrepo', branch: 'master')
      }
    }
  }
}