pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                scripts{
                sh """

                echo "building"


                """
                }
            }
        }
        stage('Test') {
            steps {
               scripts{
                sh """
                echo "testing"
                """               
                }
            }
        }
        stage('Deploy') {
            steps {
                scripts{
                    sh """
                    echo "deploying"


                    """
                }
            }
        }
    }
}