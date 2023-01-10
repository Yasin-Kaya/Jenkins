pipeline {
  agent {label 'postgresql'}

  stages {
    stage('PostgreSql') {
      steps {
        sh '''
          sudo yum update -y
          sudo amazon-linux-extras install ansible2
          ansible --version
        '''
      }
    }
  }
}
