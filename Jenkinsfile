pipeline {
  agent any
  stages {
    stage('DEV') {
      steps {
        git(url: 'git@github.com:jpabbisetty/EnterpriseDevOps.git', branch: 'master', credentialsId: 'oa45hcg48rnsmL3edyEP')
      }
    }
  }
}