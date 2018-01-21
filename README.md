# tomcat-war-development
Basic setup to connect Eclipse, Maven and Tomcat

Currently tested on W10/Fedora27:
 
 Eclipse-oxygen:
 * JST Web dev extensions, incl adapters
 
 Tomcat 8.5 - local dev installation
 
 Maven
 
 * incl configuring ~/.m2/settings.xml for tomcat7:deploy
```xml
  <servers>
    <server>
      <id>TomcatServer</id>
      <username>admin</username>
      <password>PASSWORD</password>
    </server>
  </servers>
 

