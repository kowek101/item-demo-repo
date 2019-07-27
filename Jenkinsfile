pipeline {
  agent any
  stages {
    stage ('test') {
      steps {
        echo "Hello, world"
      }
    }
    stage ('Build Docker image') {
      steps {
        sh '''
        docker build --rm -t foo .
        '''
      }
    }
  }
}
