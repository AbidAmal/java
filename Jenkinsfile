pipeline {

   agent any

    options{
            timeout(unit:'SECONDS', time:5)
           }
     stages {
  
        stage('Test') {
            
            steps {
                echo 'Testing'
             
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
            }
        }

   }
