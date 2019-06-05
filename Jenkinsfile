pipeline {
  agent any
 
  tools {nodejs "node"}

  stage('Change dir') {
      steps {   
        dir ('/var/www') {
          sh 'pwd'
          sh 'ls'
        }

       } 
    } 

}    
 