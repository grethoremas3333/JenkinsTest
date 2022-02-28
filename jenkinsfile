node {
    stage('Clone and Acces') {
        git credentialsId: 'd7db5923-aacd-4b96-845c-ca2702a88370', url: 'https://github.com/grethoremas3333/JenkinsTest.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
