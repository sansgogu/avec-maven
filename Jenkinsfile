pipeline {
    agent any

    tools {
        maven 'M2_HOME'
    }

    stages {
        stage('Build Maven') {
            steps {
                dir('student-management') {
                    sh 'mvn -version'
                    sh 'mvn clean package'
                }
            }
        }
    }
}
