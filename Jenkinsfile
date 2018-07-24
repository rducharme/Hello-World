pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "hello world build"'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing in progress'
      }
    }
    stage('Deploy') {
      steps {
        sleep 10
        echo 'Deployment done'
      }
    }
  }
}