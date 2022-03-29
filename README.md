# SFML template for windows or linux

### Arch linux

```
$ sudo pacman -Sy sfml
```

### Debian

```
$ sudo apt-get install libsfml-dev
```

### Windows

Follow instructions [here](https://vcpkg.io/en/getting-started.html) and then:
```
.\vcpkg.exe install sfml:x64-windows
```

#### If you are using VScode on windows

1. Create `.vscode` folder in your project directory
2. Add `{"cmake.generator": "Visual Studio 17 2022",}`
    - Use `cmake -h` if you dont have VS or you have different version
