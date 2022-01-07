node {
    stage('Build') {
        sh 'cd /home/ubuntu/test'
        sh 'git clone https://github.com/seunghwan-won/testjenkin.git'
        echo '빌드'
        echo 'git test'
    }
    stage('Test') {
        echo '테슽'
        sh 'ls -al'
        echo 'git test2'
    }
    stage('Deploy') {
        echo '배포'
    }
}