pipeline {
 agent { label 'UBUNTU' }
 stages {
 stage('build and package') {
 steps {
  git branch: 'declarative' ,
  url: 'https://github.com/lordsrikrishna/spring-petclinic.git'
  sh 'mvn package'
       }
 
                            }
        }
 
        }
