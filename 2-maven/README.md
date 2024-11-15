# Setting up Maven project

Generate template project:

```
mvn archetype:generate
```

Install dependencies and build `JAR` file:

```
mvn install
```

## Versions

`java -version`:

```
openjdk version "21.0.5" 2024-10-15 LTS
OpenJDK Runtime Environment Temurin-21.0.5+11 (build 21.0.5+11-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.5+11 (build 21.0.5+11-LTS, mixed mode, sharing)
```

`javac -version`:

```
javac 22.0.2
```

`jar --version`:

```
jar 22.0.2
```

`mvn -version`:

```
Apache Maven 3.9.9 (8e8579a9e76f7d015ee5ec7bfcdc97d260186937)
Maven home: C:\ProgramData\chocolatey\lib\maven\apache-maven-3.9.9
Java version: 22.0.2, vendor: Oracle Corporation, runtime: C:\Program Files\OpenJDK\jdk-22.0.2
Default locale: ru_RU, platform encoding: UTF-8
OS name: "windows 11", version: "10.0", arch: "amd64", family: "windows"
```