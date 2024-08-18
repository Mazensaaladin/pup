pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'build'
        echo 'build completed'
        echo 'build comppo'
      }
    }

    stage('test stages ') {
      parallel {
        stage('test stages ') {
          steps {
            echo 'Running test2'
          }
        }

        stage('Test1') {
          steps {
            echo 'running test1'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployment compl'
      }
    }

  }
}