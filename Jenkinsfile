node
{
  stage("fetch")
  {
    //git "https://github.com/natarajshares/java-mvn"
    sh "git clone https://github.com/natarajshares/java-mvn.git"
    sh "git branch && cd java-mvn && ls"
  }
  
  stage("build")
  {
    echo "hello packaging..."
    //bat(/mvn package/)
	sh "cat pom.xml"
	sh 'mvn package'
  }
  
  
}
