pipeline {
    agent any
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE = 'sqlite'
       
    }
    

    
    stages{
        
        environment {
   SAUCE_ACCESS = credentials('testPipe')
}
        
        stage ('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}




