pipeline {
    agent any

    stages {
        stage('LS') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Git Log') {
            steps {
                sh 'git log --oneline -1'
            }
        }
    }
}
