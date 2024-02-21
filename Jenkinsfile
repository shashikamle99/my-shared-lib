@Library("shared-lib-shashi") _

pipeline {
    agent any
    stages {
        stage('Code Checkout') {
            steps {
                script {
                  echo ${WORKSPACE}
                  def workingDir = checkoutCode("https://github.com/shashikamle99/my-shared-lib.git", "main")
                  echo $workingDir
                }
            }
        }
    }
}