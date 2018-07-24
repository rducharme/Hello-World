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
        mail(subject: 'deployment step', body: 'The code is now deployed', from: 'Robert.Ducharme@prolifics.com', to: 'rducharme@skybeam.com')
        echo 'Deployment done'
      }
    }
  }
}