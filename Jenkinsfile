pipeline {
    agent any

    stages {
        stage("Checkout") {
            when {
                branch 'git' // Change 'git' to actual branch name if needed
            }
            steps {
                git url: 'https://github.com/Esthersurya1223/Calculator-houari.git'
            }
        }

        stage("Maven Build") {
            when {
                branch 'maven' // Change 'maven' to actual branch name if needed
            }
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
