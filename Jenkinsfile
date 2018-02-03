pipeline {
    agent { docker 'openjdk:7' }
    stages {
        stage('build') {
            steps {
                sh 'javac -d . HelloWorld/src/hello/HelloWorld.java'
                sh 'java -cp . hello.HelloWorld'
            }
        }
    }
}
