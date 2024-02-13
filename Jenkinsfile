pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date'''
        echo 'test step'
        echo 'deploy'
      }
    }

    stage('deploy') {
      steps {
        sh '''date
ls
'''
      }
    }

  }
}