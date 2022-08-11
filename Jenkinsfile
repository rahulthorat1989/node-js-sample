pipeline {
  agent any
    
  tools {nodejs "nodejs-10.5.3"}
    
  stages {    
    stage('Build') {
      steps {
        sh 'npm install'
         sh '<<Build Command>>'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
