pipeline {
    options {
        dryRun(onBranchIndexing: true)
    }

    agent { label 'master' }

    stages {
        stage('Test') {
            sh 'echo "Test !"'
        }
    }
}
