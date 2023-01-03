pipeline {
    agent { label 'slave_1' }
    stages {
        stage('Fetch and Run Branch') {
            steps {
                git branch: 'main', url: 'https://github.com/syednazimshah/nazim-testing-pipeline.git'
                sh 'chmod u+x run.sh'
                sh './run.sh'
            }
        }
    }
}
