@Library("shared-lib@main") _

pipeline {
    agent any
    stages {
        stage('Code Checkout') {
            steps {
                script {
                  def workingDir = checkoutCode("https://github.com/shashikamle99/my-shared-lib.git", "main")
                  echo $workingDir
                }
            }
        }
    }
}