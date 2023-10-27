pipeline {
    agent { 
        docker { 
            image 'sychonet/bazelisk:latest' 
        } 
    }
    
    stages {
        stage('build') {
            steps {
                sh 'whoami'
                sh 'bazelisk --version'
                sh 'bazelisk build //src/app1/hello'
            }
        }
    }
}
