pipeline {
    agent { 
        label "bazelisk-agent"
    }
    
    stages {
        stage('build') {
            steps {
                bazelisk --version
            }
        }
    }
}
