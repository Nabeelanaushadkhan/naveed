pipeline {
    agent any

    stages {


        stage('Clean Build') {
            steps {
                sh 'mvn clean package
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

        stage('Run Application') {
            steps {
                sh 'mvn clean package'
            }
        }
}
}

