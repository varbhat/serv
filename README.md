<h1 align="center">serv</h1> 
<p align="center">HTTP File/Directory Server</p>

<br>

## Introduction
- `serv` is HTTP File/Directory Server.
- It can serve Directories, Files and SPAs over HTTP(or HTTPS).


## Installation

You can download binary for your OS from [Releases](https://github.com/varbhat/serv/releases/latest) . Also , if you have [Go](https://golang.org/) installed , you can install `torpar` by typing this in terminal.

```bash
go install github.com/varbhat/serv@latest
```

## Usage
```bash
serv is HTTP File/Directory Server

Usage of serv:
 -addr    <addr> Listen Address (Default: ":9955")
 -cert    <path> Path to TLS Certificate (Required for HTTPS)
 -dir     <path> Directory to Serve (Default: Current Directory)
 -key     <path> Path to TLS Key (Required for HTTPS)
 -spa     <opt>  SPA Mode
 -help    <opt>  Print this Help
 ```
 
 ## License
 [GPLv3.0](LICENSE)
 
