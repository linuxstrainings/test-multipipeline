pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
          sh 'echo "npm install..."' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application  functionality..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
