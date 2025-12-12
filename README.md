### Demo simplest GWT + Bootstrap3

Used Java 8:

````shell
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
````

Generate wrapper:

````shell
mvn -N wrapper:wrapper
````

Package project:

````shell
./mvnw package
````

Start project:

````shell
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64

./mvnw gwt:run
````

[http://127.0.0.1:8888/SeedWebApp.html](http://127.0.0.1:8888/SeedWebApp.html)


![doc/screen1.png](doc/screen1.png)

## Seed Web App For GwtBootstrap3

Starter project with everything you need to start a GwtBootstrap3 and GWT project.

This project can be run using Maven http://maven.apache.org

`mvn gwt:run`


Enjoy!
