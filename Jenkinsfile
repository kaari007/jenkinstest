pipeline {
   agent any
   stages {
       stage("init") {
           steps {
               sh "echo running test init."
           }
       }
       stage("build") {
           steps {
               sh "echo running test build."
           }
       }
       stage("test") {
           steps {
               sh "echo running test stage."
           }
       }
       stage("deploy") {
           steps {
               sh "echo running deploy stage."
           }
       }
   }  
}
