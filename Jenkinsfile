pipeline {							
    triggers {
    pollSCM('') // Enabling being build on Push
    }
    agent any						
    stages {						
        stage('Build') {			
            steps {					
                echo 'Test 2..'	
            }						
        }							
        stage('Test') {				
            steps {					
                echo 'Testing..'	
            }						
        }							
        stage('Deploy') {			
            steps {					
                echo 'Deploying....'
            }						
        }							
    }								
}									
