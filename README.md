## Maven flavoured AndEngine

The only difference with this fork is the addition of a Maven `pom.xml`. 

When installing this using `mvn install`, the AndEngine is installed into your local 
Maven repository as an [APKLIB](https://code.google.com/p/maven-android-plugin/wiki/ApkLib). 

Once the APKLIB is installed into your local Maven repository, simply add the following 
dependency to your Android project to include AndEngine:

```xml
<dependency>
  <groupId>org.andengine</groupId>
  <artifactId>andengine</artifactId>
  <version>1.0-SNAPSHOT</version>
  <type>apklib</type>
</dependency>
```
