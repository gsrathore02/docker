pipeline {
  agent {
    dockerfile {
      filename 'wordpress'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'echo "Hello World"'
      }
    }
  }
}