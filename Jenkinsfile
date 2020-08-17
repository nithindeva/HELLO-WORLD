pipeline {
     agent any
     
     stages {
         stage ('compile') {
              steps {
              withMaven{maven : 'maven_3_5_0') {
                   sh 'mvn clean compile'
              }
           }
       }
         stage ('Testing') {
         
             steps {
                withMaven(maven :'maven 3_5_0') {
                sh 'Testing'
                }
             }
         }
       
           stage ('Deploy') {
           steps {
                withMaven(maven : 'maven_3_5_0')  {
                     sh 'Deploy'
                 }
              }        
          }
      }
 }
