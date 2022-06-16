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
                    url: 'https://github.com/komalkasa162/devops-practise.git'
            }
        }
        stage("Message"){
            steps{
                
                echo "Git repo has been successfully checked out"
            }
        }
    }
}
