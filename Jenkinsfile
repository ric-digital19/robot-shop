pipeline {							
    agent any
    triggers {
    pollSCM('') // Enabling being build on Push
    }
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
