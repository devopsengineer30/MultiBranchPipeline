pipeline {   
    agent any

    stages {   
        stage('dev branch') { 
            steps { 
               sh 'echo "This is dev branch' 
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
