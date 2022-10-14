pipeline {
  environment {
    imagename = "Imran615/hacicenkins"
    registryCredential = 'dockerhub'
    dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
 //       git([url: 'https://github.com/imran615/hacicenkins.git', branch: 'master', credentialsId: 'github'])
 	checkout scm

      }
    }
    stage('Building image') {
      steps{
     
      sh "echo AWSKEY && sleep 10"


          }
      }
   
    
    
  }
}
