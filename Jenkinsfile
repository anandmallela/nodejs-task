pipeline{
 agent any
 stages {
  stage('Fetch code') {
    steps {
     git branch: 'main' , url: 'https://github.com/anandmallela/nodejs-task.git'
   
   }
  }
    stage('Build'){
     steps {
      sh 'npm install' 
    }
   }
     stage('Test'){
      steps {
       sh 'npm test' 
   } 
  }
 }
}
