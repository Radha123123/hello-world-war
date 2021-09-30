pipeline {
    agent any
    environment {
        PATH="/usr/share/maven/bin/:$PATH"
    }
    stages {
        stage('prctice2') {
            steps {
               // echo 'Hello World'
               git 'https://github.com/Radha123123/hello-world-war.git'
            }
        }    
        stage('practice3') {
            steps {
                echo 'Hello World'
                sh "mvn clean package"
            }
        }
    }
}
