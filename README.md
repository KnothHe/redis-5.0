# Redis-5.0 Source Code

## Note

Original README.md is README-origin.md

## What is this repository for

- This repository just saved Redis 5.0 release source code

## How to get Redis 5.0 source code

- You can just clone from [offical repository](https://github.com/antirez/redis) use following command

```bash
git clone https://github.com/antirez/redis.git --branch 5.0 --single-branch
```

- Surely, you can just clone this repository

## Tools that can be used to read source code

- [Source Trail](https://www.sourcetrail.com)

This is what I used to read Redis 5.0 source code

### Steps

1. You need to generate a `compile_commands.json` file. The tool [`bear`](https://github.com/rizsotto/Bear) may help. Then go to the project root directory, run following command.
```bash
bear make
```
2. Use `sourcetrail` Create a new project and Select `C/C++ from compilation Database` as `Source Group` and select previous `compile_commands.json`.

- [CLion](https://www.jetbrains.com/clion/)

Amazing!