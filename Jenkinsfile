node {
  stage('SCM') {
    checkout scm
  }
  stage('SonarQube Analysis code') {
    def mvn = tool 'Default Maven';
    withSonarQubeEnv() {
      sh "${mvn}/bin/mvn clean verify sonar:sonar -Dsonar.projectKey=maevn"
    }
  }
}





