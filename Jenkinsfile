pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build quietPeriod: 4, job: 'myfirstjob'
            }
        }
        stage('Test') {
            steps {
                echo 'testing'
            }
        }
        stage('Release') {
            steps {
                echo 'releasing'
            }
        }
      stage('Deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
