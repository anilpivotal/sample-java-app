pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                 //echo "Hello World!"
                //sh "pack build myapp"
               // sh "docker login registry-1.docker.io"
                //sh "pack build anilpivotal/my-image:myapp --publish"
                sh "pb image apply -f pb-image-apply.yaml"
                //sh "kubectl delete deployment myapp -n test"
                //sh "kubectl delete services myapp -n test"
               // sh "kubectl apply -f my-app.yml -n test"
                
                //   sh "docker run --rm -p 8080:8080 myapp" 
            }
        }
    }
}

