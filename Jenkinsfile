pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building App...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing App...'
                // sh 'gcloud compute zones list'
                sh 'gcloud compute scp /var/lib/jenkins/workspace/Devops-Project_main_main/index.html root@apache-server:/var/www/html --zone=us-central1-f'
            }
      }
   }
}
