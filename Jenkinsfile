pipeline {
    agent any

    stages {
        stage('pull code ') {
            steps {
                git 'https://github.com/DaisyGu2/spring-analysis.git'
            }
        }
        stage('build code ') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
