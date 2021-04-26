pipeline{
    agent any

    stages{
        stage('Print current Branch') {
          
            stage('Main') {
                    echo "Main branch"
                }
            stage('temp-branch') {
                    echo "Main branch"
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
