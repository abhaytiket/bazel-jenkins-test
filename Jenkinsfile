pipeline {
    agent { 
        docker { 
            image 'gcr.io/bazel-public/bazel:6.4.0' 
        } 
    }
    stages {
        stage('build app1') {
            steps {
                sh 'docker pull maven:3.5.0'
            }
        }
    }
}
