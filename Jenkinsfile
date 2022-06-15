pipeline {
    agent any

    stages {
        stage('cleanup')
        {
            steps{
                deleteDir()
            }
        }
        stage('Git Clone') {
            steps {
                
                    git branch : 'main',
                    url: 'https://github.com/komalkasa162/git_practise.git'
            }
        }
        stage("Message"){
            steps{
                
                echo "Git repo has been successfully checked out"
            }
        }
    }
}
