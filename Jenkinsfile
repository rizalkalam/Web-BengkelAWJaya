pipeline{
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

       stage('Deploy HTML File') {
            steps {
                sh 'sudo cp -r /home/rizalkalam/.jenkins/workspace/bengkelawjaya/* /var/www/bengkelawjaya.my.id/html/'
                // sh 'sudo cp -r /home/rizalkalam/.jenkins/workspace/SupremeAcademy/assets/* /var/www/worldinyourhand.my.id/html/assets/'
                // sh 'sudo cp -r /home/rizalkalam/.jenkins/workspace/SupremeAcademy/style/* /var/www/worldinyourhand.my.id/html/style/'
            }
        }
    }
}