pipeline {

   agent any

    options{
            timeout(unit:'SECONDS', time:5)
           }
     stages {
        
         
        stage('Build') {
        
            steps {
                echo 'Building'
               
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
            }
        }
 
  
        stage('Test') {
            
           
            steps {
                echo 'Testing'
             
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
            }
        }
           
        stage('Deploy') {
            
          
            steps {
                echo 'Deployment'
              print ' deployed successfully'
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
            }
        }
          
        stage('Release') {
            
           
            steps {
                echo 'Releasing'
             
                git branch: 'main', credentialsId: 'myGithub', url: 'https://github.com/AbidAmal/java.git'
            }
        }
    }
    
   }
