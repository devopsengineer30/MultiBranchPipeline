pipeline {   
    agent any

    stages {   
        stage('main branch') { 
            steps { 
               sh 'echo "This is main branch' 
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