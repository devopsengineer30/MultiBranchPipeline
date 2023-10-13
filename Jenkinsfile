pipeline {   
    agent any

    stages {   
        stage('qa branch') { 
            steps { 
               sh 'echo "This is qa branch' 
            }
        }
     
        stage('Test') { 
            steps { 
               sh 'echo "Testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
