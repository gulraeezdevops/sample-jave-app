@Library('jenkins_shared_lib') _

pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                script{
                    // git branch: 'main', url: 'https://github.com/gulraeezdevops/sample-jave-app.git'

                    gitCheckout{
                        branch: "main",
                        url: "https://github.com/gulraeezdevops/sample-jave-app.git"
                    }
                }
            }
        }
    }
}