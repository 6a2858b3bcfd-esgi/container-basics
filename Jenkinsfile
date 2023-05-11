pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'docker buildx build -t php .'
      }
    }

  }
}