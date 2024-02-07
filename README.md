# spring-boot-starter redirect unkown urls to index.html

## Why?

When you build a single page application (SPA) with a framework like Angular, React, or Vue, you will have a single `index.html` file that is served to the client. The client-side routing is then handled by the JavaScript framework. When you deploy your application to a server, you will want to serve the `index.html` file for all unknown URLs. This is because the client-side routing should handle the URL and display the correct content.
