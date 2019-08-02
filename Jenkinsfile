pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                //sh "pack build myapp"
                sh "pack build anilpivotal/my-image:myapp-v1 --publish"
                sh "kubectl apply -f my-app.yml"
                
                //   sh "docker run --rm -p 8080:8080 myapp" 
            }
        }
    }
}

