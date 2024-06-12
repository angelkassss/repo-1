pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'dev', // Change to 'master' for the master branch pipeline
                credentialsId: 'your-github-credentials-id', // Replace with your credentials ID (optional)
                url: 'https://github.com/yourusername/repo-1.git'
            }
        }
        // Add your build and test stages here
    }
}

