import groovy.json.JsonSlurperClassic

def jsonParse(def json) {
    new groovy.json.JsonSlurperClassic().parseText(json)
}
pipeline {
  agent { label 'principal' }
  environment {
    appName = "variable" 
  }
  stages {

 stage("paso 1"){
     
      steps {
          script {			
           cd C:\Users 
        }
      }
    }
  }
  post {
      always {          
          deleteDir()
           dir
      }
      success {
            cd C:\Users\Edilson
        }

      failure {
            cd C:\Users\Edilson\Downloads
      }
      
  }
}  

