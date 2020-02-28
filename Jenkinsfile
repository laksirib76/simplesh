pipeline {
  agent {
    node {
      label 'sltest'
    }

  }
  stages {
    stage('init') {
      steps {
        sh '''echo "hello"
ping -c 5 localhost'''
      }
    }

    stage('Test') {
      steps {
        sh 'echo "hello 3"'
      }
    }

  }
}
