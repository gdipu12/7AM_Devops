pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'app deployment "this is stage1"'
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