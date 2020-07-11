pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "building the application...."
                sh 'python3 file1.py'
            }
        }
        stage("test") {
            steps {
                echo "testing the application...."
            }
        }
        stage("deploy") {
            steps {
                echo "deploying the application...."
            }
        }
    }
}
