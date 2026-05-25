pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'touch  "$USERPROFILE/Desktop/empty-file.txt"'
                echo 'Hello from Pipeline!'
            }
        }
    }
}
