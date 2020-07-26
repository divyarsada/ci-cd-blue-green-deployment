pipeline {
  agent any
  stages {
    stage('Create EC2 Instance') {
      steps {
        ansiblePlaybook playbook: 'main.yaml', inventory: 'inventory'
      }
    }
  }
}
