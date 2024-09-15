pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh '''echo"hello world"
'''
            echo 'build completed'
          }
        }

        stage('build1') {
          steps {
            echo 'hello from build1'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'test completed'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy is completed'
      }
    }

  }
}