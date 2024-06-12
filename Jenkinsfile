pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World ${env.BUILD_NUMBER}'
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
