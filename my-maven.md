---
layout: default
---

### How to access my Maven Repository.

#### Maven
```xml
<repository>
   <id>kingtux-repo</id>
   <url>https://repo.kingtux.me/repository/maven-public/</url>
</repository>

```
#### Gradle
```java
repositories {
  maven { url 'https://repo.kingtux.me/repository/maven-public/' }
}
```

### Why?
I use my own Maven Repository for new projects, personal projects, or projects that I don't want to be on the central. 
