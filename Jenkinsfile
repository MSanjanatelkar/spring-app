pipeline {
    agent any

    tools {
       maven 'maven-3.5'
   }
   stages{
    stage('cloning the code'){ 
        steps{
            git 'https://github.com/spring-projects/spring-petclinic.git'
        }
    }
    stage ('maven build'){
        steps{
            sh 'mvn clean install -DskipTests=true'
        }
    }
  }
}
   
   
   

        
