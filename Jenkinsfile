pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                build 'testing'
                echo 'Hello World'
                git 'https://github.com/sagar-work/jenkins-gitlab-public.git'
            }
        }
        stage('Build ') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Depolaying '
            }
        }
        stage('Test') {
            steps {
                echo 'Testing '
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing '
            }
        }
    }
}
