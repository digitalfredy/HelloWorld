pipeline {
  agent {
    docker {
      image 'openjdk:11'
    }
  }

  stages {
    stage('Compilation') {
      steps {
        sh 'java HelloWorld.java'
      }
    }
  }
}
