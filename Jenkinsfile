pipeline {
    agent any
    stages {
        
        stage('run') {
            steps {
                echo 'Running build automation'
                sh './gradlew bootRun'
                
            }
        }
    }
}
