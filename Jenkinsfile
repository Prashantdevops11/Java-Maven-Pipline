Pipeline {
   agent any
     tools {
       maven 'M2_HOME'
       }
      stages{
      stage('checkout the project') {
        steps{
         git branch: 'main', url: 'https://github.com/Prashantdevops11/Java-Maven-Pipline.git'
         }
       }
       stage('Build'){
         steps {
         sh mvn -B -DakipTests clean package'
         }
        } 
      }
}
