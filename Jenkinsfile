pipeline{
    agent any
    stages {
    stage('build'){
    steps{
    sh 'ant -f build.xml -v'
    sh 'echo "This is pipeline script"'
    }
    }
    stage('testing') {
    steps {
    sh 'ant -f build.xml -v'
}
    }
    }
}

