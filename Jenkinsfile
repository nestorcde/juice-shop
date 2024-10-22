pipeline {
    agent any
    tools {nodejs "Node18"}

    stages {
        stage('Build') {
            steps {
		sh 'echo "Hola Mundo"'
                sh 'npm install'
            }
        }
    }
}
