pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'app deployment'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "this is stage2"'
      }
    }

    stage('deploy') {
      steps {
        sh 'java info | java -version'
      }
    }

  }
}