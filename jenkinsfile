node {
    stage('clone') {
        git 'https://github.com/houdaBENNCIR/jenkins-helloworld'
       }
    stage('build') {
       sh label: '', script: 'javac Main.java'  
} 
     stage('run') {
        sh label: '', script: 'java Main' 
}
}