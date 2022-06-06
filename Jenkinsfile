pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                powershell 'python -m py_compile sources/add2vals.py sources/calc.py'
            }
        }
    }
}