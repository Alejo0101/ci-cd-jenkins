pipeline {
    agent any

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
