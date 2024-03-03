# NetArmor
### Reactor Netty Provider
This provider is used to integrate NetArmor Enhanced security features to Reactor Netty based servers.

# Installation
Please note, that you should first add exploit.org's repository.

### Maven:
```xml
<repositories>
    <repository>
        <id>exploit</id>
        <name>Exploit Repository</name>
        <url>https://maven.exploit.org</url>
    </repository>
</repositories>
```
```xml
<dependency>
    <groupId>org.exploit</groupId>
    <artifactId>netarmor-reactor-netty</artifactId>
    <version>1.1</version>
</dependency>
```

### Gradle:
```groovy
repositories {
    mavenCentral()

    maven {
        url("https://maven.exploit.org")
    }
}
```
```groovy
implementation 'org.exploit:netarmor-reactor-netty:1.0'
```