node
{
  stage("fetch")
  {
    git "https://github.com/G-Gowtham/java-automation.git"
  }
  
  stage("build")
  {
    echo "hello packaging..."
    //bat(/mvn package/)
	cat pom.xml
	sh 'mvn package'
  }
  
  
}
