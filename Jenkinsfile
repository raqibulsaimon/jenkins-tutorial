pipeline
{
  agent
  {
    label "node1"
  }
  stages
  {
    stage('Build')
    {
      steps
      {
        echo "Building..."
        sh 'ls -al'
        sh 'pwd'
      }
    }
    stage ('Test')
    {
      steps
      {
        echo "Testing"
      }
    }
    stage("Deploying")
    {
      steps
      {
        echo "Deploying"
      }
    }
  }
}
