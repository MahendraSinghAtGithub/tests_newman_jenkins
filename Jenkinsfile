node{
    stage('scm checkout'){
      git 'https://github.com/MahendraSinghAtGithub/tests_newman_jenkins'
      sh 'npm install'
      sh 'npm run api-test'
    }
}
