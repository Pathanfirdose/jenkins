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

    // post build 
    post {
        always {
            echo 'i will say hello always'
        }
        success {
            echo 'i will say hello when success'
        }
        failure {
            echo 'i will when failure'
        }
    }
}