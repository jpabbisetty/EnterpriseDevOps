pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        git(url: 'git@git.digitalharbor.us:devops/scripts.git', branch: 'master', credentialsId: '08576372-f1e5-470c-9890-37ad5f6f8a6c')
      }
    }
  }
}