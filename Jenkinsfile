pipeline {

    agent { dockerfile {

    filename "/Dockerfile"
    registryUrl ""
    registryCredentialsId 'dockerHub'


    }}
    stages {
        stage('Build') {
            steps {
                echo 'hello !'
                sh 'echo LM_LICENSE_FILE = $LM_LICENSE_FILE'
            }
        }
