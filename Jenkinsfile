pipeline {
  agent any

  stages {
    stage('Echo') {
      when {
        not {
          branch 'master'
        }
      }
      steps {
        sh 'echo Branch name: ${BRANCH_NAME}'
      }
    }
  }
}
