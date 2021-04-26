pipeline{
    agent any

    stages{
        stage('Print current Branch') {
          
            stage('Main') {
                steps {
                        echo "Main branch"
                    }
                }
            stage('temp-branch') {
                steps {
                        echo "temp-branch"
                    }
                }
            post {
                success {
                    echo "App started succesfully"
                }
                failure {
                    echo "Some error ocurred"
                }
            }
        }
    }
}
