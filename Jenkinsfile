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
   }
}