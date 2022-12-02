pipeline {
   agent any
   stages{

    stage("Build Code"){
      steps {
         script {
            sh "mvn install"
         }
      }
    }
   }
}