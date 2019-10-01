pipeline {							
    agent any
    job('dou') {
    triggers {
        scm('')
     }
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
