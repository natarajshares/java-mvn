node
{
  stage("fetch")
  {
    //git "https://github.com/natarajshares/java-mvn"
    sh "git clone https://github.com/natarajshares/java-mvn"
    sh "cd java-mvn"
  }
  
  stage("build")
  {
    echo "hello packaging..."
    //bat(/mvn package/)
	sh "cat pom.xml"
	sh 'mvn package'
  }
  
  
}
