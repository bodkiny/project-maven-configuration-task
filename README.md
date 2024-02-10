### Installing the `com.javarush: desktop-game-engine:1.0` dependency from the `lib/` directory to the local repository:

Run the following command in the terminal:
```mvn install:install-file -Dfile=<path-to-file> -DgroupId=<group-id> -DartifactId=<artifact-id> -Dversion=<version> -Dpackaging=<packaging>```

Where:
- `<path-to-file>`: the path to the file to be installed on your computer.
- `<group-id>`: `com.javarush`.
- `<artifact-id>`: `desktop-game-engine`.
- `<version>`: `1.0`.
- `<packaging>`: `jar`.