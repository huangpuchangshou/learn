pipeline {
    agent any
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE = 'sqlite'
       
    }
    

    
    stages{
        
       
        
        stage ('Build') {
             environment {   SAUCE_ACCESS = credentials('testPipe')}
            
            steps {
                sh 'printenv'
            }
        }
    }
}




