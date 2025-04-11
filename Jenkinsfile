pipeline {
    agent any // Uruchom na dowolnym dostępnym agencie

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Tutaj normalnie byłyby kroki budowania, np. mvn compile
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Tutaj normalnie byłyby kroki testowania, np. mvn test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Tutaj normalnie byłyby kroki deploymentu
            }
        }
    }
}
