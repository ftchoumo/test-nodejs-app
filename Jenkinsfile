pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'sudo apt-get install npm'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'sudo echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'sudo echo "deploying application..."'
         }

     }
  
   	}

   }


