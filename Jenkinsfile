pipeline{
    agent {
        label "ws"
    }
    stages{
        stage('Lint Checks'){
            steps{
                sh "echo ***** Starting Style Checks ***** "
                //sh "mvn checkstyle:check || true"
                sh "echo ***** Style Checks are completed ***** "

            }
        }
        stage('Static Code Analysis'){
            steps{
                sh "echo ***** Starting Static Code Analysis ***** "

            }
        }
    }
}