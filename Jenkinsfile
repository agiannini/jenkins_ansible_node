pipeline {
  agent any
  stages {
    stage('clean') {
      steps {
        sh 'rm -rf /etc/ansible/*'
      }
    }

    stage('MakeDir') {
      steps {
        sh 'echo makeDir'
      }
    }

    stage('move') {
      steps {
        sh 'mv * /etc/ansible'
      }
    }

    stage('run') {
      steps {
        sh 'ansible-playbook /etc/ansible/playbook.yml'
      }
    }

  }
}