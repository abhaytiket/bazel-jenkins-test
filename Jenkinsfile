pipeline {
    agent { label 'bazelisk-agent' }
    
    stages {
        stage('build') {
            steps {
                sh 'bazelisk build //src/app1'
            }
        }
    }
}
