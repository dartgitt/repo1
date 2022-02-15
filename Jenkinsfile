pipeline {
   agent any
   stages{
      stage('Paso 1'){
         steps{
            sh 'echo Paso 1'
         }
      }
      stage('Verificando Docker'){
         steps{
            sh 'docker images'
         }
      }
   }
}