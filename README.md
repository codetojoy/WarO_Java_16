
WarO_Java
=========

a Java submission for War-O as a code exercise

* this project uses:
    - Java 8 streams
    - Java 10 `var`
    - Java 15 (second preview) `record`
    - Java 15 (preview) `sealed`
    - Java 16 from [here](https://melix.github.io/blog/2021/03/gradle-java16.html) with Gradle 7 preview
* goals include: a functional style, immutable objects, minimal use of for-loops
* Spring's Java configuration is used to configure players

To Build:
---------

* tested with 16.ea.36-open via SDKMan!

useful commands:

* `sdk env`
* `./gradlew clean test`
    - on Windows, use `gradlew.bat`
* `./gradlew run`
* `./gradlew build`

See test output in `~/build/reports/tests/index.html`

See executable zip in `~/build/distributions`

To Run:
---------

* configure `src/main/java/org/peidevs/waro/config/Config.java`
* `./gradlew run`
    - on Windows, use `gradlew.bat`

Rules:
---------

Rules are [here](Rules.md).
