pipeline
{
    agent any
    stages{
        stage('Build')
        {
            steps{
                script{
                    bat 'docker build -t my-node-app .'
                }
            }
        }
        stage('Test')
        {
            steps{
                script{
                    echo 'running'
                }
            }
        }
        stage('Deploy')
        {
            steps{
                script{
                    echo'deploying...'
                }
            }
        }
    }
}


