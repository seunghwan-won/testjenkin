node {
    stage('Build') {
        echo '빌드'
         sh '''\
            pwd
            ls -al
            # 디렉토리 존재 유무 확인
            If [ ! -d /var/lib/jenkins/workspace/jenkins_pipeline/testjenkin ] ; then
             cd /var/lib/jenkins/workspace/jenkins_pipeline/testjenkin
             git pull
            else
             cd /var/lib/jenkins/workspace/jenkins_pipeline
             git clone https://github.com/seunghwan-won/testjenkin.git
             cd testjenkin
            fI
            ls -al
            sudo ./gradlew clean build
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