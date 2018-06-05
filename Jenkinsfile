pipeline {
  agent any
  stages {
    stage('DEV') {
      steps {
        git(url: 'https://github.com/jpabbisetty/EnterpriseDevOps.git', branch: 'master', credentialsId: '70593cd5d515abc7e05095feb200f7b4f0e847c2', changelog: true)
        sh '''sh \'\'\'
echo "Executing Gradle Build"
cd ${WORKSPACE}/initial
gradle build --info
gradle build
\'\'\''''
      }
    }
  }
}