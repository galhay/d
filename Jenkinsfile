pipeline {
    agent any

    stages {
        stage('create') {
            steps {
                sh 'touch emptyfile.txt'
            }
        }
         stage('print') {
            steps {
                echo "Hello from Pipeline!"
            }
        }
    }
}
