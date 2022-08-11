pipeline {
  agent any
    
  tools {nodejs "nodejs-15"}
    
  stages {    
    stage('Build') {
      steps {
        sh 'npm install'
         sh 'npm build'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
