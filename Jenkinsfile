pipeline {
    agent any
    stages {
        
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'
                
            }
        }
        stage('run') {
            steps {
                echo 'Running build automation'
                sh './gradlew bootRun --no-daemon'
                
            }
        }
    }
}
