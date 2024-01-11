pipeline {
  agent {
    label 'ansible'
  }
  stages{
    stage('test my agent'){
      steps{
        sh 'pwd'
        sh 'ls'
        sh ' touch serge'
        sh 'ls'
      }
    }
  }
}
