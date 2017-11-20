pipeline {
    agent any
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE = 'sqlite'
        SAUCE_ACCESS = credentials('testPipe')
    }
    

    
    stages{
        stage ('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}




