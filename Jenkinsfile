@Library("Shared") _ 
pipeline{
    agent any
    
    stages{
        stage("Hello")
        {
            steps{
                script{
                    hello()
                }
            }
        }
        stage("Code"){
            steps{
              echo "This cloning the code"
              clone("https://github.com/LondheShubham153/django-notes-app.git", "main")
              echo "code clone successful"
                
            }
            
        }
        stage("Build"){
              steps{
                echo "This is building the code"
            }
            
        }
        stage("test"){
              steps{
                
                echo "This is testing the code"
            }
            
        }
        stage("deploy"){
              steps{
                echo "This is deploy the code"
            }
            
        }
    }
}
