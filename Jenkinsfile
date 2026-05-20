pipeline{
    agent any

    tools {
        nodejs 'node26'
    }

    stages{
        stage('VM Node Version') {
            steps {
                sh '''
                node -v
                npm -v

                '''
            }
        }

    }
}