https://www.youtube.com/watch?v=pwP9zimYec4

C:\phil\dev\projects\examples\jenkins\java
mvn archetype:generate -DgroupId=com.pmk.app -DartifactId=maven-jenkins-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

$$$$$

echo "# maven-jenkins-app" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pmkent/maven-jenkins-app.git
git push -u origin master

git remote add origin https://github.com/pmkent/maven-jenkins-app.git
git push -u origin master