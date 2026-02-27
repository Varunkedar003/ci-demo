    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'ls'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'cat wrongfile.txt'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging application...'
                sh 'echo "Artifact created" > build.txt'
            }
        }
    }
}
