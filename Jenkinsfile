pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh script:'''
                    cd todo-backend
                    npm install
                    node app.js
                '''
            }
        }

        stage ("Build Frontend") {
            steps {
                sh script:'''
                    cd todo-fronted
                    npm install
                    npm start
                '''
            }
        }
    }
}