pipeline {   
    agent any

    stages {   
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch..."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
