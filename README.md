# totppoc

Proof of concept of using TOPT with https://github.com/samdjstevens/java-totp.

## history

```
mvn archetype:generate -DgroupId=com.infodesire.totppoc -DartifactId=totppoc -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

# after adding dependency
mvn dependency:resolve
```

## build

```
mvn verify
```

## run

```
mvn verify exec:java
```