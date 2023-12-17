pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            
            }
        }
       stage('Deploy') {
            steps {
                git credentialsId: 'git', url: 'https://github.com/sagar-bhavsar1/sagar-bhavsar1.git'
            
            }
        }
    }
}
