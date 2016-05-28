Using Maven to generate a test project
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

Git tip
git update-index --assume-unchanged .metadata/*


Workflow to upload all this to the private repository:

Created local repository. Created remote repo.
git remote add pmt https://github.com/pankajmauryatimes/hellospring.git
git remote -v
git remote show pmt
git pull https://github.com/pankajmauryatimes/hellospring.git
git push pmt master
