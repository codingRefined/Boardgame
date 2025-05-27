pipeline {
    agent any

   tools {
  jdk 'jdk17'
  maven 'mavenLatest'
}
    stages {
       
        stage('compile'){
            steps{
            sh 'mvn compile'
        }
        }
         stage('test'){
            steps{
            sh 'mvn test'
        }
        }
        stage('build'){
            steps{
            sh 'mvn package'
        }
        }
        
        
    }
    
    
}
