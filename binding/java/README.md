# Things to know when building this

* Remember to build jars with:
```
$ JAVA_HOME=/path/to/java/1.8.x/home ./gradlew jars
```
Selenium requires JAVA 8.

# Uploading Jars to Sonatype OSS

1. ./gradlew uploadArchives
2. Continue publishing of archives at https://oss.sonatype.org/index.html#view-repositories
