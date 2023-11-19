## Environment setup
### C++ Tool chain
Must have C++ tool chain installed on the system. See instructions at https://code.visualstudio.com/docs/cpp/config-wsl
```shell
sudo apt-get install build-essential gdb
```

### Paket
http://fsprojects.github.io/Paket/get-started.html#NET-Core-preferred
```shell
dotnet new tool-manifest
dotnet tool install paket
dotnet tool restore
```

## Dependencies
Dependencies are managed using Paket. Edit `paket.dependencies` and run `update_deps.sh` to apply updates.
