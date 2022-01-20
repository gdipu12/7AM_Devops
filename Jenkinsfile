pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "this is stage1"'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "this is stage2"'
      }
    }

    stage('deploy') {
      steps {
        sh 'jenkins info | grep -i version'
      }
    }

  }
}