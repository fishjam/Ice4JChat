### Ice4J Chat demo(with maven)
- generate maven framework by:

```
mvn archetype:generate -DgroupId=com.fishjam -DartifactId=Ice4JChat 
-DarchetypeGroupId=com.github.charlie-cityu.archetypes 
-DarchetypeArtifactId=docs-city-archetype-quickstart -DinteractiveMode=false 
-DarchetypeCatalog=local
```
- copy and modify code from [hankcs/IceNAT](https://github.com/hankcs/IceNAT)
- build & run
```
  mvn clean package
  target\Ice4JChat-1.0-SNAPSHOT-jar-with-dependencies.jar
```

### TODO:
  - Add SDP support? refer [Cmdmac/IceNAT](https://github.com/Cmdmac/IceNAT)