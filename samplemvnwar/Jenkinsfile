pipeline {
   agent any

   stages {
      stage('Git checkout') {
         steps {
            git credentialsId: '5eed4d0c-ac98-49aa-9f10-cbe3524a6297', url: 'https://github.com/arbiswas1990/samplemavenwar.git'
         }
      }
      stage('build') {
         steps {
             
             sh '''
            echo 'I am in build'
            '''
         }
      }
      stage('Deploy') {
         steps {
            echo 'I am in deploy'
         }
      }
   }
}
