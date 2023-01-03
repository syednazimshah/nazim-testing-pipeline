pipeline {
    agent any
    stages {
        stage('Fetch and Run Branch') {
            steps {
                git branch: 'main', url: 'https://github.com/syednazimshah/nazim-testing-pipeline.git'
                sh './run.sh'
            }
        }
    }
}
