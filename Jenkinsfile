pipeline {
    agent {
        docker {
            image 'node:18'
            args '-u root'
        }
    }
    stages {
        stage('Instalar dependencias') {
            steps {
                sh 'npm install'
            }
        }
        stage('Mostrar versión de node y npm') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}
