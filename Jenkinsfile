pipeline {
agent any
stages{
stage ('scm'){
steps {
git 'https://github.com/Netha1999/New_file.git'
}
}
stage ('build'){
steps {
bat label: '', script: 'mvn clean'
bat label: '', script: 'mvn install'
}
}
}
}
