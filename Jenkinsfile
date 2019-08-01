pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "pack build myapp"
                sh "docker run --rm -p 8080:8080 myapp"
            }
        }
    }
}

