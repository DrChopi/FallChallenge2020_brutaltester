# Fall Challenge 2020

[Fall Challenge 2020](https://github.com/CodinGame/FallChallenge2020) adapation for [brutaltester](https://github.com/dreignier/cg-brutaltester).
This project is based on work of [fala13](https://github.com/fala13) for **LegendsOfCodeAndMagic**.

## Prerequisite

- [Java JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html).
- [Maven](https://maven.apache.org/download.cgi) Apache tool.
- [cg-brutaltester](https://github.com/dreignier/cg-brutaltester) tool.

## Installation

- `cd <project>`
- `mvn clean install package`

## Usage

You can rename the `.jar` file named `fall-2020-1.0-SNAPSHOT.jar` in `/target`
Now your can do for example :

```bash
java -jar btester.jar -r "java -jar fall2020.jar" \
     -p1 "python ..\test.py" \
     -p2 "python ..\test.py" \
     -n 5 -t 2 -s -l "../logs"
```

For more usages see the [doc](https://github.com/dreignier/cg-brutaltester).