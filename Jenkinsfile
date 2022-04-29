pipeline {
    agent any
    stages{
        stage ('Build'){
            steps{
                echo 'Building...'
                echo 'Abhiram'
                bat 'python lab.py'
            }
        }
        stage ('Test'){
            steps{
                echo 'Using maven'
            }
        }
    }
}
