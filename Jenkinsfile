pipeline {
  agent {
    node {
      label 'jenkins'
    }

  }
  stages {
    stage('Git clone') {
      steps {
        sh 'echo "cloning git repo"'
      }
    }

    stage('Build stage') {
      steps {
        sh 'echo "build stage"'
      }
    }

  }
}