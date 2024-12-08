pipeline {
    agent any
    stages {
       stage('Checkout') {
            steps {
                git branch: 'main', credentialsId: 'c61a17f6-b4a7-4b85-b962-69ec0f613dd0', url: 'https://github.com/gdpk6248/cosign.git'
            }
        }
   }
}



