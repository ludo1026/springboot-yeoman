# springboot-yeoman
SpringBoot &amp; Yeoman

* yo : yeoman project for front pages
* pom.xml : maven pom 
  * dev : use grunt independently to generate frontal pages
  * prod : use grunt from maven to generate frontal page which will be include in the final packaging

# dev
Start the project :
 * mvn spring-boot:run
 * cd yo
 * grunt dev

# prod
Build the project :
 * mvn spring-boot:run -Pprod

