pipeline {
    agent {label 'dev'}

    stages {
        stage('git') {
            steps {
                git credentialsId: 'f0019360-719d-4f0f-9c61-71bfce1d6139', url: 'https://github.com/vikasarisela/testing.git'
            }
        }
    }
}
