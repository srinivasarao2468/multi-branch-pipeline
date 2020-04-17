pipeline {
  agent any
  stages {
    stage('release build') {
      when {
        branch 'release*'
      }
      steps {
        sh 'echo Building on ${BRANCH_NAME}...'
      }
    }
    stage('master build') {
      when {
        branch 'master'
      }
      steps {
        sh 'echo Building on ${BRANCH_NAME}...'
      }
    }
    stage('master build') {
      when {
        branch 'master'
      }
      steps {
        sh 'echo Building on ${BRANCH_NAME}...'
      }
    }
  }
}
