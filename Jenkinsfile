pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        git(url: 'git@git.digitalharbor.us:devops/scripts.git', branch: '*/master', credentialsId: 'jenkins_git_user')
      }
    }
  }
}