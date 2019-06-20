# dependency-check-example
Example on using dependency-check

## Dependency Check
To execute a dependency-check scan you can call the maven command 

**dependency-check:check** (plugin: org.owasp:dependency-check-maven)

This will show the results in the command line and create an html report.

## Dependency Tree
If it is not clear which source a dependency belongs to you can create a dependency tree using the maven command 

**dependency:tree** (plugin: org.apache.maven.plugins:maven-dependency-plugin)
 
This will show a dependency tree in the command line.

## Update Check
If you want to check the used dependencies for updates you can achieve this using the maven command 

**versions:display-dependency-updates** (plugin: org.codehaus.mojo:versions-maven-plugin)
 
This will show a dependency tree in the command line.

## Useful links
* [OWASP Dependency Check](https://www.owasp.org/index.php/OWASP_Dependency_Check)