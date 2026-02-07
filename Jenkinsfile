pipeline {
  agent { label 'my' }

  stages {
    stage('Test') {
      steps {
        sh 'echo "Running on node my"'
        sh 'hostname'
      }
    }
  }
}

