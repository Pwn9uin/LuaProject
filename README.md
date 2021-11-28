# lua-5.4.4-sandbox-escape

### Create docker image

```sh
docker build --tag rce/x64:latest x64
```
### How to run

```sh
docker run -it rce/x64:latest /bin/bash
```

### Exploit

```sh
/LUA/lua/lua /LUA/exploit.lua
```