pipeline {
    agent {
        label 'linux'
    }

    stages {

//         stage('Checkout') {
//     steps {
//         git branch: 'master',
//             url: 'https://github.com/SaiTejaBale/CICD.git'
//     }
// }

       stage('Find Files') {
            steps {
                sh '''
                    pwd
                    ls -la
                    find . -name pom.xml
                '''
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
                echo 'success'
            }
        }
    }
}
