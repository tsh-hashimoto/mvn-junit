MavenでJUnitのテストを実行する

Javaバージョン21でJUnit5のプロジェクトを作成する場合
```
`mvn archetype:generate -DgroupId=com.example -DartifactId=<Project Name> -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DjavaVersion=21`
```

`src/main` の方に通常のJavaソースコード、`src/test` の方にテストコードを格納する。

`mvn test` でテストを実行する
