pipeline {
  agent any
  parameters { string(name: 'JSON', defaultValue: 'staging', description: '') }
  stages {
      stage ("Build") {
        steps {
         script{
            def jsonObj = readJSON text: "${params.JSON}"
            echo "Running build Automation"
        } }
      }
  }
}








       
