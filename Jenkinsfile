pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                bat 'wmic computersystem get name'
                bat 'echo %PATH%'
                echo bat(returnStdout: true, script: 'set')
                bat 'mvn --version'
            }
        }
    }
}