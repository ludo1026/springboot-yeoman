# springboot-yeoman
SpringBoot &amp; Yeoman

* yo : yeoman project for front pages
  * Gruntfile.js : copy the "serve" build task to a new task named "dev" which does not contain "server:livereload" in its subtasks list 
* pom.xml : maven pom 
  * dev : use grunt independently to generate frontal pages
  * prod : use grunt from maven to generate frontal page which will be include in the final packaging

# dev
Start the application :
 * mvn spring-boot:run

# grunt
Start the application with Maven and Grunt :
 * mvn spring-boot:run -Pgrunt
 * cd yo
 * grunt dev

# prod
Package the application :
 * mvn package -Pprod

