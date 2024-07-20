# rustyroulette

A pretty simple library I wrote for my reddit cake day, which I intend of publishing on r/rustjerk.

## Features

- 6 different ways of doing pretty felonious things in Rust
- selected at random!!

These include:

1. a simple segmentation fault
2. a stack overflow
3. a memory leak
4. lots and lots of panics
5. a compiler stack overflow
6. unwrapping a present (results in a massive panic due to the shock of being gifted nothing)

## What did I learn from this?

Actually, this project wasn't completely useless (although it is).
I've learned quite about how to trick the compiler, messed a bit w/ unsafe code etc.
Also, I leared how good the rust compiler actually is. I had to search for quite some time to get some of my shenanigans to work when compiling in release mode.
The optimizations are really good!

## Usage

Just clone this repo and compile it.

```bash
cargo run [-r]
```

In order to see the compiler overflow, you need to uncomment line 66, and recompile.
