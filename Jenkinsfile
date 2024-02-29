
pipeline {
    agent {
        docker { image 'node:20.11.1-alpine3.19' }
    }
    stages {
        stage('Hello') {
            steps {
                echo  'hai linh main'
            }
        }
        stage('read Readme') {
            when {
                branch "fix-*"
            }
            steps {
                sh '''
                cat README.md
                '''
            }
        }
    }
}