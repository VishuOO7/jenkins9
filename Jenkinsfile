
pipeline {

agent any

stages {

stage('Build') {

steps {
sh 'javac hello.java'
echo "HelloWorld"

}

}

stage('Run') {

steps {

sh 'java hello'

echo "HelloWorld"
}
}
}
}
