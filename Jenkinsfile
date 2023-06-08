pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh "ls"
                sh "cd todo-backend"
                sh "ls"
                sh "npm install"
            }
        }

        // stage ("Build Frontend") {
        //     steps {
        //         sh "ls"
        //         sh "cd todo-fronted"
        //         sh "ls"
        //     }
        // }
    }
}