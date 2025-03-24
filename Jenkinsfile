pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/your_username/DjangoDockerProject.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t your_dockerhub_username/assignment_project .'
            }
        }
        stage('Push to Docker Hub') {
            steps {
                withDockerRegistry([credentialsId: 'docker-hub-credentials', url: '']) {
                    sh 'docker push your_dockerhub_username/assignment_project'
                }
            }
        }
    }
}
