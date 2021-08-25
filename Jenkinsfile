pipeline {
    agent any
   
    stages {
        stage ('Speak') {
            when {
                // Only say hello if a "greeting" is requested
                expression { params.Stages == 'greeting' }
            }
            steps {
                echo "Hello, bitwiseman!"
            }
        }
        stage ('Say')
        {
            when {
                expression {params.Stages == 'silence'}
            }
            steps {
                echo "Hello, kanishka!"
            }
        }
    }
}
