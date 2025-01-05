pipeline {
  agent {
    docker {
      image 'docker.io/library/busybox'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'echo "Hello World!" > index.html'
      }
    }

  }
}