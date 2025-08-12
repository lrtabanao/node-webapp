pipeline {
    agent {
    node {
        label 'agent1'
        customWorkspace '/home/ltabanao'
    }
}
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
