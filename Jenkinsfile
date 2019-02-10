pipeline {
    agent any
    triggers {
        upstream 'Task1, Hello, '
    }
    stages {
      stage('FIRST-JOB'){
        steps{
    git 'https://github.com/rubeenashaik/task7.git'
        }
  }
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
