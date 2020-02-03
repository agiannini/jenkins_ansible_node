pipeline {
  agent any
  stages {
    stage('ping') {
      steps {
        sh 'ansible -m ping all'
      }
    }

    stage('run') {
      steps {
        sh 'ansible-playbook playbook.yml'
      }
    }

  }
}