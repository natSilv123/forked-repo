xpipeline {
    agent any  // Ejecuta en cualquier nodo disponible
    stages {
        stage('Checkout') {
            steps {
                // Clonar el código desde GitHub
                git url: 'https://github.com/natSilv123/forked-repo.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                // Simula un paso de compilación
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                // Simula pruebas unitarias
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                // Simula un despliegue
                echo 'Deploying the application...'
            }
        }
    }
}

