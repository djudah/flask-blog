Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                bat 'K:\Dev\tools\apache-maven-3.3.3\bin\mvn --version'
            }
        }
    }
}