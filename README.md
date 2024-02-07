# spring-boot-starter fallback page: redirects unknown urls to index.html

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
    <artifactId>spring-boot-starter-fallback-page</artifactId>
    <version>...current version...</version>
</dependency>
```

## Run the example

Start the [spring boot example application](./example) and open [http://localhost:8080](http://localhost:8080) in your
browser. A welcome message is displayed.

Navigate to any other path, e.g. [http://localhost:8080/supermarket](http://localhost:8080/supermarket). The welcome
message is still displayed.

## Is it good?

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)

[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=bugs)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=coverage)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=neuefische_spring-boot-starter-fallback-page&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=neuefische_spring-boot-starter-fallback-page)
