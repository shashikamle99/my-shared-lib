@Library('shared-lib-shashi')_

pipeline{
    agent any
    stages{
        stage('shared-lib-use'){
            steps{
                script{
                    calculator.add("20","30")
                }
            }
        }
    }
}