# Gradle with Groovy

To initialize a Gradle project with Groovy, run:

```
gradle init --type java-application --dsl groovy
```

To build the project, run:

```
./gradlew build
```

To build `JAR` file, run:

```
./gradlew jar
```

Resulting `JAR` file will be located in `build/libs` directory.

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

`gradle -v`:

```
------------------------------------------------------------
Gradle 8.11
------------------------------------------------------------

Build time:    2024-11-11 13:58:01 UTC
Revision:      b2ef976169a05b3c76d04f0fa76a940859f96fa4

Kotlin:        2.0.20
Groovy:        3.0.22
Ant:           Apache Ant(TM) version 1.10.14 compiled on August 16 2023
Launcher JVM:  22.0.2 (Oracle Corporation 22.0.2+9-70)
Daemon JVM:    C:\Program Files\OpenJDK\jdk-22.0.2 (no JDK specified, using current Java home)
OS:            Windows 11 10.0 amd64
```