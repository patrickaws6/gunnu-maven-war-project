# gunnu-maven-war-project
# For ---------war----------- file  
# cmd cli server aws ec2
  mvn archetype:generate \
  -DgroupId=com.example \
  -DartifactId=mywebapp \
  -DarchetypeArtifactId=maven-archetype-webapp \
  -DinteractiveMode=false
# mvn clean package
It will build the (war) package with al the required classes.
# push the code to github
git init \n
-git add . 
-git status
git commit -m "initial commit: index.jsp" or
git branch -M main
   git remote add origin https://github.com/patrickaws6/gunnu-maven-war-project.git
   git push -u origin main
git pull --rebase origin main
git push -u origin main
#check the repository & confirm
