pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        git(url: 'git@git.digitalharbor.us:devops/scripts.git', branch: '*/master', credentialsId: 'oa45hcg48rnsmL3edyEP')
      }
    }
  }
}