pipeline {
    agent any
    stages {
        stage("git"){
            steps {
                git branch: 'main', credentialsId: 'gitcred', url: 'https://github.com/sphurthigithub/New-repo1.git'
            }
        }
    }
}
