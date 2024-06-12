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
        // This is where I would add my test and dev branches but idk how to do that so imma leave it

    }
}

