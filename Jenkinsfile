pipeline {
    agent any

    stages {
        stage('create') {
            steps {
                touch emptyfile.txt
            }
        }
         stage('print') {
            steps {
                echo "Hello from Pipeline!"
            }
        }
    }
}
