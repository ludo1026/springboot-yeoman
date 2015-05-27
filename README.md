# springboot-yeoman
SpringBoot &amp; Yeoman

* yo : yeoman project for front pages
  * Gruntfile.js : copy the "serve" build task to a new task named "dev" wich does not contain "server:livereload" in its subtasks list 
* pom.xml : maven pom 
  * dev : use grunt independently to generate frontal pages
  * prod : use grunt from maven to generate frontal page which will be include in the final packaging

# dev
 * mvn spring-boot:run

# grunt
Start the project :
 * mvn spring-boot:run -Pgrunt
 * cd yo
 * grunt dev

# prod
Build the project :
 * mvn package -Pprod

