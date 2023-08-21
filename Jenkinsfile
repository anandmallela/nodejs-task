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
      sh 'mvn install' 
    }
   }
     stage('Test'){
      steps {
       sh 'mvn test' 
   } 
  }
 }
}
