pipeline {
    agent {
        docker {
            image 'python:3.11'
        }
    }
    stages {
        stage('Run Script') {
            steps {
                sh 'python helloworld.py'
            }
        }
    }
}
