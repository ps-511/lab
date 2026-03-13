pipeline{
  agent any

  stages{
    stage{"Compile Java Program'"){
      steps{
        bat 'javac HelloWorld.java'
      }
      stage{'Run java program'){
        steps{
          bat 'java HelloWorld'
        }
      }
           }
    }
         }
