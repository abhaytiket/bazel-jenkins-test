pipeline {
    agent { 
        label "bazelisk-agent"
    }
    
    stages {
        stage('build') {
            steps {
                sh 'echo $HOSTNAME'
            }
        }
    }
}
