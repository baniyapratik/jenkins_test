pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          awsCodeBuild projectName: 'Jenkins_Test',
                       credentialsId: 'JenkinsTest',
                       credentialsType: 'jenkins',
                       region: 'us-west-2',
                       sourceControlType: 'project'

        }
      }
    }
}
