@Library('ChimeraTK') _

pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "My BUILD step..."
        test.MyTest
      }
    }
  }
}
