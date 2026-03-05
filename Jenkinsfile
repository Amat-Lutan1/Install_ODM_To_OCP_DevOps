pipeline {
    agent any

    stages {
        stage('Initialization') {
            steps {
                echo 'Initialization'
                bat 'oc project odm-sandbox'
            }
        }
    }
}
