# javaProperties

Check your java system properties

## Build

    mvn clean package

## Execute

    mvn exec:java

or

    java -jar target/*.jar

## Example:

```
$ mvn exec:java 
[INFO] Scanning for projects...
[INFO] 
[INFO] ---------------------< org.albfan:javaProperties >----------------------
[INFO] Building javaProperties 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] >>> exec-maven-plugin:1.2.1:java (default-cli) > validate @ javaProperties >>>
[INFO] 
[INFO] <<< exec-maven-plugin:1.2.1:java (default-cli) < validate @ javaProperties <<<
[INFO] 
[INFO] 
[INFO] --- exec-maven-plugin:1.2.1:java (default-cli) @ javaProperties ---
awt.toolkit:sun.awt.X11.XToolkit
classworlds.conf:/usr/share/maven/bin/m2.conf
file.encoding:UTF-8
file.separator:/
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
```

## Credits

Based on post from https://mkyong.com/java/how-to-list-all-system-properties-key-and-value-in-java/ 
