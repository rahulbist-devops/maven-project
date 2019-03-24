pipeline{
   agent any
   stages {
     stage ('Build'){
     steps {
         sh 'mvn clean package'
         // archiveArtifacts artifacts: '/var/lib/jenkins/workspace/maven-project/artifacts/abc.war'
         archiveArtifacts artifacts: '**/target/*.war'
     } 

    }

   }

}
