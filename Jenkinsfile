pipeline {
    agent any
    stages{
        stage('WORKING STAGE'){
            steps {
                
                bat 'xcopy /S "*" "C:/xampp/htdocs/exp-4-patel" /Y'
            }
        }

        stage('FINAL STAGE'){
            steps{
                echo 'Done!'
            }
        }
    }
}
