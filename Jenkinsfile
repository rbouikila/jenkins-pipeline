node {
  stage('Clone') {
    git 'https://github.com/rbouikila/jenkins-pipeline.git'
    
  }
  stage('Build') {
    sh label: '', script: 'javac main.java'
  }
  stage('Run') {
    sh label: '', script: 'java Main'
  }
}
