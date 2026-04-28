pipeline {
    agent {
        node {
            label 'ROBOSHOP'
        }
    }
    stages {
        stage('Build') {
            steps {
                script {
                sh """

                echo "building"
                


                """
                }
            }
        }
        stage('Test') {
            steps {
               script {
                sh """
                echo "testing"
                """               
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    sh """
                    echo "deploying"


                    """
                }
            }
        
    // post build
    post {
        always {
            echo "I will always says hello again"
        }
        success {
            echo "pipeline success"
        }
        failure {
            echo "pipeline failure"
        }
    }

    }
}
}