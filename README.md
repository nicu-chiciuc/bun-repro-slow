When running `bun install` it seems to hang:

```sh
time bun install
bun install v1.0.1 (31aec4eb)
  🔍 bun-types [6/6] 
error: ConnectionRefused downloading package manifest bun-types
error: bun-types@latest failed to resolve

________________________________________________________
Executed in  450.16 secs      fish           external
   usr time   23.79 millis    6.70 millis   17.09 millis
   sys time   34.56 millis    2.89 millis   31.67 millis
```

# How to reproduce

```sh
bun init
bun install
```

