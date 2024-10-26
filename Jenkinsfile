#hi

pipeline{
    agent {label "slave"}

    stages{
satge ("checkout scm"){
        steps {
                script {
                    // Clone the specified repository
                    sh 'git clone https://github.com/shreeveer/django-notes-app.git'
                }
            }
        }
        stage("docker build"){
            steps{
                echo "buid"
            }
        }
        stage("docker push"){
            steps{
                echo "docker push"
            }
        }
        stage("deploy"){
            steps{
                echo "deployed"
            }
        }
    }
}
