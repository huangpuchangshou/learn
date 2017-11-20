pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                retry(5){ 
                    sh 'echo "Hello World"'
                }
                
                timeout(time: 5, unit: "SECONDS"){
                sh ''' 
                    echo "Multiline shell steps works too"
                    ls -lah
                    sleep 50000
                    '''
                }
            }
        }
    }
}


