pipeline {
   agent any 

   stages {
    stage("Create zip file"){
        steps {
            sh 'zip middleware-scripts-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md'
            echo "files successfully zipped"
        }
    }
   }
}