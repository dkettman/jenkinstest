pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "This is the beginning"'
                sh 'go version'
                sh 'echo "This is the end"'
            }
        }
    }
}
