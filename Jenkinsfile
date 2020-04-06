pipeline {
  agent any
  stages {
    stage('build') {
      when {
        branch 'release*'
      }
      steps {
        sh 'echo Building ${BRANCH_NAME}...'
      }
    }
  }
}
