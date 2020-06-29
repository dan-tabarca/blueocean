pipeline {
  agent {
    docker {
      image 'jenkinsci/blueocean'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'ls -lr'
      }
    }

    stage('test') {
      steps {
        sh 'cat blueocean'
      }
    }

    stage('success') {
      steps {
        sh 'echo "success"'
      }
    }

  }
}