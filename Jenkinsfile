pipeline {
    agent any
  stages{
    stage('main-branch') {
    when {
        branch 'main'
    }
    steps {
        echo 'run this stage - ony if the branch = main branch'
    }
}
  }
}
