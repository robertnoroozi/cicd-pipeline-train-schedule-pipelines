
Jenkinsfile (Declarative Pipeline)

pipeline {
    stages {
        stage('build') {
            steps {
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/*.zip'
            }
        }
    }
}

