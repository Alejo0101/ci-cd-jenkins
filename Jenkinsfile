pipeline {
    agent {
        docker {
            image 'node:18'
        }
    }

    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }

        stage('Build Success') {
            steps {
                echo 'Build completado correctamente 🎉'
            }
        }
    }
}
