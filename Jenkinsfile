pipeline {
    agent any
  
       parameters{
           string(defaultValue: 'Prasanna', name: 'User-name')
           string(defaultValue: 'Prasanna2', name: 'User-name2')
           
       }
    

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', credentialsId: 'b9b26ea6-c7c1-48be-854f-dc35dca8e102', url: ' https://github.com/nirajku102/Git_Workshop_2.git'
                sh 'ls -lrt '
                echo 'Hello World'
            }
        }
        stage('satge2'){
            steps{
                echo 'satge2'
            }
        }
        stage('satge3'){
            steps{
                echo 'satge3'
            }
        }
    }
}
