pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('') {
      steps {
        dockerNode(dockerHost: 'idk', image: 'centos:centos7')
      }
    }
  }
}