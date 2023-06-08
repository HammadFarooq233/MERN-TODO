pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh script:'''
                    ls
                    cd todo-backend
                    ls
                '''
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