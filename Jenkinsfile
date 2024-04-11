pipeline {
    agent any

    stages {
        stage('versionTest') {
            steps {
                // Exécute la commande "docker version" pour vérifier la version de Docker
                bat 'docker version'
                 bat 'kubectl version'

                
            }
        }
    }
}
