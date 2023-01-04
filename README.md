# Rose Packages

This repository is used to publish packages for the the-roses organisation.

## How to use?

**NOTE:** A common mistake is, that you haven't been authenticated with github packages. See more information [here](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry#authenticating-to-github-packages).

### Maven
**For artifact *downloads*:**
```xml
<repository>
  <id>github</id>
  <url>https://maven.pkg.github.com/the-roses/rose-packages</url>
</repository>
```

**For artifact uploads:**
```xml
<distributionManagement>
   <repository>
     <id>github</id>
     <url>https://maven.pkg.github.com/the-roses/rose-packages</url>
   </repository>
</distributionManagement>
```
