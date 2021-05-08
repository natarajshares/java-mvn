node
{
  stage("fetch")
  {
    //git "https://github.com/natarajshares/java-mvn"
    sh 'rm -r java-mvn || echo "hi"'
    sh "git clone https://github.com/natarajshares/java-mvn.git"
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
