pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'gradle --version'
		sh './gradlew build'
            }
        }
    }
}
