pipeline {
    agent any 
  stages {
    stage ('1 choice') {
      when {
                expression { choice == '1'}
            }
            steps {
                echo "Hello, Choice 1!"
            }
    }
    stage ('2 choice') {
      when {
                expression { choice == '2'}
            }
            steps {
                echo "Hello, Choice 2!"
            }
    }
  }
}
