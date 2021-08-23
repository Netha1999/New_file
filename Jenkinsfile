pipeline {
agent any
stages{
stage ('Getting my code from scm'){
steps {
git 'https://github.com/Netha1999/New_file.git'
}
}
stage ('build my file'){
steps {
bat label: '', script: 'mvn clean'
bat label: '', script: 'mvn install'
}
}
}
}
