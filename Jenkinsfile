pipeline {
    agent any   
    stages {
        stage('Fetch')
        {
            steps
            {
                script
                {
                    if(params.Stages == "Stage-1")
                    {
                        git url : "https://github.com/kanishka012/Doc.git"
                    }
                    else
                    {
                        pwd
                    }
                }
            }
        }
        
     
    }  
  }
