
pipeline{
  agent any 
  tools{
    maven'Maven 3.6.0'
    jdk'jdk 11.0.6'}
  
  stage('SCM Checkout'){
    git'https://github.com/Ebony005/pmaven'
    }
      stage('Compile-Package'){
      sh'mvn package'
      }}
