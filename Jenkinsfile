pipeline {
agent any
stages{
  stage('Build'){
    steps{
    sh '/opt/bitnami/jenkins/jenkins_home/workspace/ clean install'
    }
    stage('Test'){
      step{
      sh '/opt/bitnami/jenkins/jenkins_home/workspace/ test'
      }
    }
  }
}
}
