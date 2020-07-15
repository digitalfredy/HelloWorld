pipeline {
  agent {
    docker {
      image 'openjdk:11'
    }
  }

  stages {
    stage('Compilation') {
      sh 'java HelloWorld.java'
    }
  }
}
