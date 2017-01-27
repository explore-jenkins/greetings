#!groovy

// simple Jenkinsfile to pull source and build

node {
       stage('source') {
          checkout scm
       }
       stage('build') {
          sh "gradle build"
       }
         
}
   
