pipeline {
    options {
        dryRun(onBranchIndexing: true)
    }

    agent { label 'master' }

    stages {
        stage('Test') {
            steps {
                sh 'echo "Test !"'
            }
        }
    }
}
