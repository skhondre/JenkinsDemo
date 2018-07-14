pipeline { 
  agent any 

         tools {
        maven 'apache-maven-3.0.1' 
      
        }
    
    stages {
         stge('First') { 
           steps { 
             cleanWs()
             bat 'java -version'
             bat 'mvn --version'
             echo 'I am first stage' 
           } 
         } 

        stage('second') { 
           steps { 
             echo 'I am second stage' 
           } 
         } 


    stage('third') { 
           steps { 
             echo 'I am third stage' 
           } 
         } 

}
}

