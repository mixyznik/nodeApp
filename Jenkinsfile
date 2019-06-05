pipeline {
  agent any
 
  tools {nodejs "node"}
stages{
  stage('Change dir') {
      steps {   
        dir ('/var/www') {
          sh 'pwd'
          sh 'ls'
        }

       } 
    } 
  } 
}    
 