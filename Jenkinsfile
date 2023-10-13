pipeline {   
    agent any

    stages {   
        stage('This is the main branch') { 
            steps { 
               sh 'echo "This is main branch"' 
            }
        }
     
        stage('build1') { 
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
