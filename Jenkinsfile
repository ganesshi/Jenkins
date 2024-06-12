pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo "Hello World ${env.BUILD_NUMBER}"
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Example Deploy') {
            when {
                branch 'master'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
