pipeline {
    agent any
 
 stages {
      stage('checkout') {
           steps {
             
                git branch: 'main', url: 'https://github.com/palakbhawsar98/JavaWebApp'
             
          }
        }
  stage('Maven Build') {
           steps {
             
                sh 'mvn clean install'             
          }
        }
  stage('Maven Test') {
           steps {
             
                sh 'mvn test'             
          }
        }		
    }
 }
