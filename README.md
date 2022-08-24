# [rust-webassembly](https://rust-web-assembly-nine.vercel.app/)

![Animação](https://user-images.githubusercontent.com/52302576/186496746-911ef777-76fc-4189-95db-e5b1a2f56156.gif)

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Vercel deploy](#vercel)

## About <a name = "about"></a>

Simple project to make use of Rust and Webassembly in image processing

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.

- [Npm](https://www.npmjs.com/package/download)
- [Rust](https://www.rust-lang.org/tools/install)

### Installing

A step by step series of examples that tell you how to get a development env running.

Git clone

```bash
git clone https://github.com/hil-beer-t/rust-WebAssembly.git
```

Check if you're inside the root folder and install npm dependencies

```bash
npm i
```

Run webpack server

```bash
npm run serve
```

Output

```bash
...
🧐  Checking for wasm-pack...

✅  wasm-pack is installed at ...\npm\wasm-pack.CMD.

ℹ️  Compiling your crate in development mode...

<i> [webpack-dev-server] Project is running at:
<i> [webpack-dev-server] Loopback: http://localhost:8080/
<i> [webpack-dev-server] On Your Network (IPv4): http://192.168.0.110:8080/
...
```

Open the browser at this url:

```
http://localhost:8080/
```

<br> 
<br>

## Vercel deploy <a name = "vercel"></a>

[https://rust-web-assembly-nine.vercel.app/](https://rust-web-assembly-nine.vercel.app/)
