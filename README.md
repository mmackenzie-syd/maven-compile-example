# maven-compile-example

### Description

This is the Maven procedure for generating a project structure and compiling using the command line.

The folder "my-app" contains the folder structure generated by maven using the command: <br/><br/>
`mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false`

"archetype" is a maven package that is used to generate the folder structure.

The folder "my-app-compiled" contains the compiled code in the target folder. This was created using the maven command: <br/><br/>
`mvn package`

The compiled code in the target folder can be executed in java using the command: <br/><br/>
`java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App` <br/><br/>
The "-cp" argument is shorthand for "class path" of the main class, which is "com.mycompany.app.App" in this example.


### Reference:

https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

