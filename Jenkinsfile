pipeline {
    agent any
     stages {
      stage ('Compile') {
            steps {
                sh 'mvn compile'
                }
            }    
        stage ('Package') {
            steps {
                sh 'mvn package'
                }
            }
        stage ('Install') {
            steps {
                sh 'mvn install'
                }
            }
        }
     }   
