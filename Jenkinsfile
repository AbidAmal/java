pipeline {

   agent any

   /* options{
            timeout(unit:'SECONDS', time:5)
           }*/
     stages {
  
        stage('Build') {
            
            steps {
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
               bat './mvn clean compiled'
            }
        }

   }
}
