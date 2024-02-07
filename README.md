# spring-boot-starter redirect unkown urls to index.html

## Why?

When you build a single page application (SPA) with a framework like Angular, React, or Vue, you will have a
single `index.html` file that is served to the client. The client-side routing is then handled by the JavaScript
framework. When you deploy your application to a server, you will want to serve the `index.html` file for all unknown
URLs. This is because the client-side routing should handle the URL and display the correct content.

## How?

In a Spring Boot application, add this dependency to your `pom.xml`:

```xml

<dependency>
    <groupId>de.neuefische.java</groupId>
    <artifactId>spring-boot-starter-redirect-unkown-urls-to-index-html</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</dependency>
```

## Run the example

Start the [spring boot example application](./example) and open [http://localhost:8080](http://localhost:8080) in your
browser. A welcome message is displayed.

Navigate to any other path, e.g. [http://localhost:8080/supermarket](http://localhost:8080/supermarket). The welcome
message is still displayed.
