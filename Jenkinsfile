node {
    stage('Build') {
        echo '빌드'
         sh '''\
            pwd
            ls -al
            git clone https://github.com/seunghwan-won/testjenkin.git
            ls -al
            cd testjenkin/
            ls -al
            ./gradlew clean build
         '''
    }
    stage('Test') {
        echo '테스트'
        sh 'pwd'
    }
    stage('Deploy') {
        echo '배포'
        sh 'pwd'
    }
}