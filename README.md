# jar-shadeds
#### java jar-shadeds arrange

+ apache hbase
```xml
<dependency>
    <groupId>org.apache.hbase</groupId>
    <artifactId>hbase-shaded-client</artifactId>
    <version>${hbase.version}</version>
</dependency>
```

+ elasticsearch-transport-client
```xml
<dependency>
  <groupId>com.github.harbby</groupId>
  <artifactId>es-shaded</artifactId>
  <version>5.6.0-1</version>
</dependency>
```
```xml
<dependency>
  <groupId>com.github.harbby</groupId>
  <artifactId>es-shaded</artifactId>
  <version>6.4.0-1</version>
</dependency>
```

+ guava 18
```xml
<dependency>
    <groupId>org.apache.flink</groupId>
    <artifactId>flink-shaded-guava</artifactId>
    <version>18.0-7.0</version>
</dependency>
```