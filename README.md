# gradle-replace-properties-resources-plugin-demo
Demonstration on how to develop a simple RESTful API using Jersey and Jetty Embedded for multiple deployment environments using a custom Gradle plugin.

- Just run "gradlew run" from the root folder and the application will compile and run.
- To use a different deployment environment values use "gradlew run -Denv=xxx", for example "gradlew run -Denv=qa" or "gradlew run -Denv=prod_2".

More detailed tutorials can be found (in spanish) at:
- http://nombre-temp.blogspot.com/2015/12/proyectos-gradle-con-multiples-ambientes.html
- http://nombre-temp.blogspot.com/2015/12/desarrollando-un-plugin-basico-de-grade.html