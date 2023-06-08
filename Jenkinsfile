pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh "cd MERN-TODO"
                sh "cd todo-backend"
                sh "npm install"
                sh "node app.js"
            }
        }

        stage ("Build Frontend") {
            steps {
                sh "cd MERN-TODO"
                sh "cd todo-fronted"
                sh "npm install"
                sh "npm start"
            }
        }
    }
}