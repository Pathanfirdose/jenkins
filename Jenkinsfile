pipeline {
    agent {
        node {
            label 'roboshop'
        }
    }
    stages {
        stage('build') {
            steps {
                script{
                    sh """
                        echo "this is build"
                    """
                }  
            }
        }
        stage('test') {
            steps {
                script{
                    sh """
                        echo "this is build"
                    """
                }
            }
        }
        stage('deploy') {
            steps {
                script{
                    sh """
                        echo "this is build"
                    """
                }
            }
        }
    }
}