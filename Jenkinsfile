pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ansible -m ping all'
      }
    }

    stage('test') {
      steps {
        sh 'pwd'
      }
    }

    stage('deploy') {
      steps {
        sh 'pwd'
      }
    }

  }
}