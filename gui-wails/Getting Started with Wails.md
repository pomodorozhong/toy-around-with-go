# Getting Started with Wails

Reference :

+ [wailsapp/wails: Create desktop apps using Go and Web Technologies.](https://github.com/wailsapp/wails)
+ [Windows :: Wails](https://wails.app/gettingstarted/windows/)
+ [Installing Wails :: Wails](https://wails.app/gettingstarted/installing/)

## Prerequisites under Windows

Install gcc and related tooling from [http://tdm-gcc.tdragon.net/download](http://tdm-gcc.tdragon.net/download).

And Then,

``` sh
go get -u github.com/wailsapp/wails/cmd/wails
wails setup
```

## Generate a new project

``` sh
wails init
```

## Build

``` sh
cd my-project
wails build
```

## Run

``` sh
.\build\myproject.exe
```
