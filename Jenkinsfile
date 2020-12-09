pipeline { 
    agent { node {label 'QA'}} 

    stages { 
        stage('Build'){
            when {
               branch 'develop'
            }
            steps{
                sh '/usr/local/bin/composer install'
           }
        }

      }
   } 
 
 
