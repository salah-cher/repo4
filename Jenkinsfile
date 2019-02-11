pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('OSver') {
      steps {
        sh ' ansible-playbook /tmp/pro2/os.yaml -i /tmp/pro2/hosts'
      }
    }
  }
}