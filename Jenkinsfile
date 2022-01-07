node {
    stage('Build') {
        sh 'cd /home/ubuntu/test'
        sh 'git clone https://github.com/seunghwan-won/testjenkin.git'
        echo '빌드'
    }
    stage('Test') {
        sh 'mvn --version'
        sh ''
        echo '테슽'
    }
    stage('Deploy') {
        echo '배포'
    }
}