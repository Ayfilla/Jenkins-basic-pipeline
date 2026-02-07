pipeline {
  agent { label 'my' }

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Run script') {
      steps {
        sh 'ls -la'
        sh './hello.sh'
      }
    }
  }
}

