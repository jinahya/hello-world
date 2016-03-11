# hello-world
## scripts
### buildall.sh
Builds ant, maven, and gradle in a row.
```
$ sh ./buildall.sh
...
```
### cleanall.sh
Cleans all build outputs.
```
$ sh ./cleanall.sh
...
$
```
## Apache Ant
```
$ ant
...
$ java -jar dst/hello-world.jar
hello, world
$
```
## Apache Maven
```
$ mvn clean package
$ java -jar target/hello-world-noversion.jar
hello, world
$
```
## Gradle
```
$ gradle build
...
$ java -jar build/lib/hello-world.jar
hello, world
$
```
## Leiningen
```
$ lein jar
...
$ java -jar target/hello-world-noversion.jar
hello, world
$
```
