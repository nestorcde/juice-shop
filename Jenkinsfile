pipeline {
    agent any
    tools {nodejs "Node20"}

    stages {
        stage('Build') {
            steps {
		sh 'echo "Hola Mundo"'
                sh 'npm install'
            }
        }
    }
}
