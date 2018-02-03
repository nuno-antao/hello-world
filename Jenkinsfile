pipeline {
    agent {
        docker {
            image openjdk:7
        }
    }                
    stages {
        stage('build') {
            steps {
                sh 'cd HelloWorld/src'
                sh 'javac hello/HelloWorld.java'
                sh 'java -cp . hello.HelloWorld'
            }
        }
    }
}
