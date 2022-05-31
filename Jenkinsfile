pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'python sources/add2vals.py 1 2'
            }
        }
    }
}