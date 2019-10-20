---
layout: default
---
### Why?
I use my own Maven Repository for new projects, personal projects, or projects that I don't want to be on the central. 

### How to access my Maven Repository.

#### Maven
```xml
<repository>
   <id>kingtux-repo</id>
   <url>https://repo.kingtux.me/repository/maven-public/</url>
</repository>

```

#### Gradle
```
repositories {
  maven { url 'https://repo.kingtux.me/repository/maven-public/' }
}
```
