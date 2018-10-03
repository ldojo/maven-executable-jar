# maven-executable-jar
super simple maven project that builds an executable jar

run this to build the jar:
```
mvn clean compile assembly:single
```

then run ```java -jar [pathToJar]``` to execute it
