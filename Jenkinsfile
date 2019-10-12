pipeline {
  agent {
    dockerfile {
      filename 'wordpress'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh '''#!/bin/bash
echo "Hello World";'''
      }
    }
  }
}