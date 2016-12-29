# Java 8 / JUnit 4 Quickstart

This is a Maven Archetype for starting a Java 8 project using JUnit 4. It includes the following:

- Configured to compile against Java 1.8
- Uses JUnit 4.12
- Provides a project readme via a `README.md`
- Automatically creates source and JavaDoc JARs when running `package`
- Configures `site` to use the more modern [Fluido skin](https://maven.apache.org/skins/maven-fluido-skin/)
- Provides a starter end-user page via a Markdown template in `src/site/markdown/index.md`
- Fixes warnings that Maven generates by default

# Usage

To create a new project using this archetype:

```bash
$ mvn archetype:generate -B -DarchetypeGroupId=org.spilth -DarchetypeArtifactId=java8-junit4-quickstart -DgroupId=com.example -DartifactId=helloworld -Dversion=1.0.0
$ cd helloworld
$ mvn package site
$ open target/site/index.html
```

For a less verbose way to use this archetype please check out [savant](http://spilth.org/projects/savant/).
