# sparkjava_war_job

A SparkJava "Hello World" web app packaged as a WAR file. Used as a sample project for a Jenkins build job.

## What's inside
- `src/main/java/HelloWorld.java`: SparkJava app with a `/hello` endpoint
- `src/main/webapp/WEB-INF/web.xml`: registers the Spark servlet filter
- `pom.xml`: Maven build, WAR packaging

## Usage
```bash
mvn clean package
```
Deploy the generated WAR from `target/` to a servlet container such as Tomcat, then open `/hello`.

## License
See [LICENSE](./LICENSE).
