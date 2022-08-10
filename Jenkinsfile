pipeline {
    options {
        timeout(time: 12, unit: 'HOURS')
        buildDiscarder(logRotator(daysToKeepStr: '30', numToKeepStr: '10', artifactNumToKeepStr: '1'))
        skipDefaultCheckout(true)
        dryRun(onBranchIndexing: true, onParametersChange: true)
    }

    parameters {
        string (
            defaultValue: 'INT5.4',
            description: 'Branch used to build packages.',
            name : 'BRANCH')
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
