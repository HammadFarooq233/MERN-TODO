pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh script:'''
                    cd todo-backend
                    npm install
                    BUILD_ID=dontKillMe node app.js &
                '''
            }
        }

        stage ("Build Frontend") {
            steps {
                sh script:'''
                    cd todo-fronted
                    npm install
                    BUILD_ID=dontKillMe npm start &
                '''
            }
        }
    }
}