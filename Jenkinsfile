node {
    stage('Build and run') {
        git branch: 'main', url: 'https://github.com/emmanuelrabot/jenkins-helloworld.git'
        sh '''
            javac Main.java
            java Main
        '''
    }
}