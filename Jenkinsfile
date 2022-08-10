pipeline {
    options {
        dryRun(onBranchIndexing: true)
    }

    agent any

    stages {
        stage('Test') {
            steps {
                sh 'echo "Test !"'
            }
        }
    }
}
