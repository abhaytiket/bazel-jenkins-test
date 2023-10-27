pipeline {
    agent { 
        docker { 
            image 'sychonet/bazelisk:latest' 
        } 
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
