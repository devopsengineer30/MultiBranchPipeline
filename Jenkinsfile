pipeline {   
    agent any

    stages {   
        stage('This is the dev branch') { 
            steps { 
               sh 'echo "This is dev branch"' 
            }
        }
     
        stage(''dev { 
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
