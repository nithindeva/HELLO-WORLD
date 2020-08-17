pipeline {
     agent any
     
     stages {
         stage ("compile") {
             
              steps {
                  echo 'Compiling the project..'
             }
        }
       
          stage ('Testing') {
         
             steps {
                 echo 'Testing the project..'
             }
        }
  
       
           stage ('Deploy') {
               
                steps {
                   echo 'Deploying project..'
               }
          }        
     }
}
