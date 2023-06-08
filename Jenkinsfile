pipeline {
    agent any

    stages {
        stage ("Build Backend") {
            steps {
                sh script:'''
                    cd todo-backend
                    npm install
                    cd ..
                    cd todo-fronted
                    npm install
                '''
            }
        }

        // stage ("Build Frontend") {
        //     steps {
        //         sh script:'''
        //             cd todo-fronted
        //             npm install
        //             BUILD_ID=dontKillMe npm start &
        //         '''
        //     }
        // }
    }
}