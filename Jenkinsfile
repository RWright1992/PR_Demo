pipeline {
    agent any
    Stages {
        Stage('Set-up'){
            Steps {sh 'echo "hello" > hello.txt'}
        }
        Stage('List files')
            Steps {sh 'ls -la'}
    }
}