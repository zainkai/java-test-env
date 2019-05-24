# Java-test-env
This is a simple test environment for java programs

## install ubuntu dependencies
```bash
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install default-jdk gradle

java -version
gradle -v
```

## project commands (gradle)
This project points to the main file in `src/main/java/playground/playground.java`

```bash
gradle build # build project

gradle run # run project

gradle clean # delete current build
```