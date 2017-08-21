pipeline {
  agent {
    docker {
      image 'docker'
      args '-v /var/run/docker.sock:/var/run/docker.sock'
    }
    
  }
  stages {
    stage('') {
      steps {
        echo 'hello world'
        sh '''docker ps -a
docker run hello-world'''
      }
    }
  }
}