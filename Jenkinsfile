pipeline {
    agent any

    stages {
        stage('run test') {
            steps {
                sh 'jmeter -n -t TaskForce_home_page.jmx'
            }
        }

    }
}