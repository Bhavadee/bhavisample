pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Bhavadee/bhavisample.git' , poll: false
            }
        }
        // Other stages here
    }
}
