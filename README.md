## MavenMCP
MavenMCP **1.8.9** with **LWJGL-3.3.6** \
Supporting `jdk-17` and higher - recommended to use `jdk-22`

## Changes
```yaml
[+] implemented lwjgl3
[-] removed forge reflector
[+] removed realms
[+] code cleanup
```

## Usage
Clone the repository, import into IntelIJ IDEA as a Maven project. \
Create a new run configuration: 
- set working directory to `workspace`, 
- set `Start` as the Main class 

If you get error with natives after running, add:
```bash
-Djava.library.path=versions/1.8.8/1.8.8-natives/
```
to VM options in the run configuration.

## Credits
[maven-mcp](https://github.com/Tecnio/maven-mcp/tree/1.8.8) |
[optifine-src](https://github.com/Hexeption/Optifine-SRC) |
[legacy-lwjgl3](https://github.com/Zarzelcow/legacy-lwjgl3/tree/main) 