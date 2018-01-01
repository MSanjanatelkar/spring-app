pipeline {
    agent any

    tools {
       maven 'maven-3.5'
   }
   stages{
    stage('cloning the code'){ 
        steps{
            git 'https://github.com/MSanjanatelkar/JenkinsPipeline/tree/master/spring-petclinic'
        }
    }
    stage ('maven build'){
        steps{
            sh 'mvn clean install -DskipTests=true'
        }
    }
  }
}
   
   
   

        
