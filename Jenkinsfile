pipeline {
 agent none
 

   stages{
    stage('Build'){
        agent { docker 'maven:3.3.3' }
      steps{
        sh 'pwd'
        sh 'cat /etc/os-release'
      }
    } 
    stage('test'){
        agent{docker 'alpine:3.20.3'}
        steps{
            sh 'pwd'
            sh 'cat /etc/os-release'
        }
    }      
   }
}