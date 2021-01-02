pipeline {
    agent { docker { image 'openjdk:14.0.2-oraclelinux8' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
