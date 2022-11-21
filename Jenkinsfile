pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Source code is cloned form git Hub'
            }
        }
        stage('Build') {
            steps {
                echo 'Building a project'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy the package into server'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing completed'
            }
        }
        stage('Release') {
            steps {
                echo 'Product release into live server'
            }
        }
    }
}
