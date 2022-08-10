pipeline {
    options {
        skipDefaultCheckout(true)
        dryRun(onBranchIndexing: true)
    }

    agent any

    stages {
        stage('Test') {
            steps {
                script {
                    println "Executed !"
                }
            }
        }
    }
}
