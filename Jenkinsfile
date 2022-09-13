pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                tag "release-*"
            }
            steps{
                echo 'release code builded'
            }
        }
    }
}
