pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('gitclone') {
      steps {
        git(url: 'https://github.com/liorkomanski/ipibackup.git', branch: 'master', changelog: true, poll: true, credentialsId: '9f3f612c-161b-48ff-93c9-e30a110eca16')
      }
    }
  }
}