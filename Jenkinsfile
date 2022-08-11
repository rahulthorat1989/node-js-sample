pipeline {
  agent any
    
  tools {nodejs "nodejs-4"}
    
  stages {    
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'npm run test'
      }
    }
  }
}
