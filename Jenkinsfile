pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           dat 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           dat 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           dat 'echo "deploying application..."'
         }

     }
  
   	}

   }
