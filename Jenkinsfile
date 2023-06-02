// Pipeline Declarativo
pipeline { 
    agent any // Requerido

    stages {
        stage('Ejecutar pruebas unitarias'){
            steps {
                echo 'Ejecutando pruebas unitarias'
            }
        }

        stage('Ejecutar compilacion'){
            steps {
                echo 'Ejecutando compilacion'
            }
        }

        stage('Ejecutar deploy'){
            when { branch 'development' }
            steps {
                echo 'Ejecutando deployment'
            }
        }
    }
}