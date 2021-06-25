pipeline {
    agent any
    

    stages {
      stage ('Initial') {
            steps {
              echo '========================================='
              echo '                INITIAL '
              echo '========================================='
              sh '''
                   echo "PATH = ${PATH}"
                   echo "M2_HOME = ${M2_HOME}"
               '''
            }
        }
        stage ('Compile') {
            steps {
                echo '========================================='
                echo '                COMPILE '
                echo '========================================='
            }
        }
        stage ('Test') {
            steps {
                echo '========================================='
                echo '                TEST '
                echo '========================================='
                 
            }
        }

        stage('SonarQube analysis') {
           steps{
               echo '========================================='
              echo '                SONARQUBE '
              echo '========================================='
           }
        }
    }
}
