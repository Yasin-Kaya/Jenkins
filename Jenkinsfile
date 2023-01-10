pipeline {
  agent {label 'postgresql'}

  stages {
    stage('PostgreSql') {
      steps {
        sh '''
          sudo yum update -y
          sudo amazon-linux-extras install ansible2
          ansible --version
          sudo amazon-linux-extras install python3
          python3 --version
        '''
      }
    }
  }
}