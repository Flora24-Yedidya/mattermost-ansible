pipeline {
agent any
  stages{
    stage('Build'){
      step{
      sh '/opt/bitnami/jenkins/jenkins_home/workspace/ clean install'
      }
    }
    stage('Test'){
      step{
      sh '/opt/bitnami/jenkins/jenkins_home/workspace/ test'
      }
    }
  }
}
