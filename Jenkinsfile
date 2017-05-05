node {
    'java-build'
    stages {
        stage('Build') {
            steps {
                checkout scm
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
