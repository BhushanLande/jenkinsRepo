pipeline {
 agent any
 stages {
 stage('build'){
 echo 'Compiling java code'
 sh 'javac hello.java'
 }
 stage('run') {
 steps {
 echo 'Running java compiled code'
 sh 'hello.java'
 }
 }
 }
}

