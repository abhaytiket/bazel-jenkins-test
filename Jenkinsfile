pipeline {
    agent { 
        docker { 
            image 'gcr.io/bazel-public/bazel:6.4.0' 
            args '--platform=linux/amd64'
        } 
    }
    stages {
        stage('build app1') {
            steps {
                sh 'bazel --version'
                sh 'bazel run --script_path=//src/app1'
            }
        }
    }
}
