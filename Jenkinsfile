pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                withEnv(['PATH+EXTRA=/usr/bin:/bin']) {
                    sh 'echo "Hello, World!"'
                }
                //sh 'echo "Without docker"'
                //echo 'test'
            }
        }

       
    }
}
