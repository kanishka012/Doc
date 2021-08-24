pipeline {
    agent any   
    stages {
        stage('Fetch')
        {
            steps
            {
                git url : "https://github.com/kanishka012/Doc.git"
            }
        }
        stage('Build')
        {
            steps
            {
                bat 'mvn clean install'
            }
        }
     
    }  
  }
