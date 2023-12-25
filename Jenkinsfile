pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'chmod +x helloworldapp'
                }
            }
        }
       
        stage('Test') {
            steps {
                script {
                    sh './helloworldapp'
                }
            }
        }
       
        stage('Info') {
            steps {
                script {
                    echo 'The app has been deployed'
                }
            }
        }
    }
}
