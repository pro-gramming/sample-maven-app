# sample-maven-app
to test the maven feature beginner level


# first thing first , most important files are pom.xml and src ( for sorce code) 
# using these files you can create your own target in which you will find your 
# war ( web application archive ) , which is used to deploy on the tomcat web server

# to build, run below command in the root directory of your application .i.e. same level as src and pom.xml files are 

docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.3-jdk-8 mvn clean install

# after this you will have your target dir

# now look at the docker file for further instructions 
# That's it for now bitch!!
