pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build the app'
            }
        }
        stage('Test') {
            steps {
                echo 'test the app'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy the app'
            }
        }
    }
  post {
     always{
       sh 'pwd'
       echo 'This is message is related to pipeline syntax'
           }
       }
}

