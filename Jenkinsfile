node {
    stage('Clone'){
         git 'https://github.com/wolfy-Crag/JenkinsHello'
    }
    stage('Build'){
        sh label: '', script: 'javac Main.java'
    }
    stage('Run'){
       sh label: '', script: 'java Main'
    }
}
