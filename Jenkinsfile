#!/usr/bin/env groovy
pipeline {
     agent any
     
     stages {
         stage ("compile") {
             
              steps {
                  echo 'Compiling the first project..'
             }
        }
       
          stage ('Testing') {
         
             steps {
                 echo 'Testing the first project..'
             }
        }
  
       
           stage ('Deploy') {
               
                steps {
                   echo 'Deploying project..'
               }
          }        
     }
}
