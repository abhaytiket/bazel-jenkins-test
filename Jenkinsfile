pipeline {
    agent { 
        label "bazelisk-agent"
    }
    
    stages {
        stage('build') {
            steps {
                sh 'bazelisk --version'
                sh 'bazelisk build //src/app1/hello'
            }
        }
    }
}
