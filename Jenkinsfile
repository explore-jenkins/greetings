#!groovy
pipeline {
    agent any 
        
        stages {
            stage('source') {
                steps {
                    checkout scm
                }
            }
            stage('build') {
                steps {
                   sh "gradle build"
                }
            }
                
        }
    
}
   
