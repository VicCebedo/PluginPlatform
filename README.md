# ServiceAsAService
A proof of concept work to eliminate the need to restart the Server after every deployment. This experimental project is running on [Vert.x HTTP Server](https://vertx.io/) where users can run any Java code by implementing a [Plugin interface](https://github.com/VicCebedo/ServiceAsAService/blob/master/plugin/src/com/cebedo/serviceasaservice/plugin/Plugin.java). Deployment can be done by uploading a compiled JAR where the Server utilizes the Java [URLClassLoader](https://docs.oracle.com/javase/7/docs/api/java/net/URLClassLoader.html) to manage the code execution.
