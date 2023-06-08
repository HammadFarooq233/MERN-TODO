pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
            sh "cd todo-backend"
            sh "ls"
            }
        }

        stage ("Build Frontend") {
            steps {
                sh "cd todo-fronted"
                sh "ls"
            }
        }
    }
}