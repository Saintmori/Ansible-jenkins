pipeline {
    agent any

    stages {
        stage('Run playbook') {
            steps {
                sh '''
                ansible-playbook ping.yml
                sh '''
            }
        }
    }
}
