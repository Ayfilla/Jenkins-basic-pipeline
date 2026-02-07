pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "Running on built-in node"'
        sh './hello.sh'
      }
    }
  }
}

