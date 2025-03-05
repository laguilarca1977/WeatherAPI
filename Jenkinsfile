pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Aquí puedes agregar tus pasos para construir el proyecto
                echo 'Construyendo el proyecto...'
            }
        }
        stage('Test') {
            steps {
                // Aquí puedes agregar tus pasos para probar el proyecto
                echo 'Ejecutando pruebas...'
            }
        }
        stage('Deploy') {
            steps {
                // Aquí puedes agregar tus pasos para desplegar el proyecto
                echo 'Desplegando el proyecto...'
            }
        }
    }
}
