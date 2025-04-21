pipeline {
    agent any

    tools {
        jdk 'Java 17'
        maven 'Maven 3.9.9'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/RajatJana/signup_page.git' // replace with your repo URL
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
