pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            sh "cd todo-backend"
            sh "npm install"
            sh "node app.js"
        }

        stage ("Build Frontend") {
            sh "cd todo-fronted"
            sh "npm install"
            sh "npm start"
        }
    }
}