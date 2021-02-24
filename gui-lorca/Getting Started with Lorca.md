# Getting Started with Lorca

Reference :

+ [zserge/lorca: Build cross-platform modern desktop apps in Go + HTML5](https://github.com/zserge/lorca)

## Prerequisites

+ Requires Chrome/Chromium >= 70 to be installed

## Run & Build the example under Windows

``` sh
git clone https://github.com/zserge/lorca.git
cd lorca/examples/hello

go run main.go

go build -ldflags -H=windowsgui
```
