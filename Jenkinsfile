pipeline {
 //agent { label 'master' }
 agent { docker 'maven:3.3.3' }
   stages{
    stage('Build'){
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
   
