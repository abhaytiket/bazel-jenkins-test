pipeline {
    agent { 
        label "bazelisk-agent-1"
    }
    
    stages {
        stage('build') {
            steps {
                sh 'bazelisk --version'
            }
        }
    }
}
