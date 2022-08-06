pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "git clone https://github.com/bgaines36/Gaines-Wordpress.git"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}