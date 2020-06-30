pipeline {
  agent {
    docker {
      image 'jenkinsci/blueocean'
      args '-p 3000:3000'
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