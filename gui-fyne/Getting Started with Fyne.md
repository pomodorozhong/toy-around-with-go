#  Getting Started with Fyne

Reference : [fyne-io/fyne: Cross platform GUI in Go based on Material Design](https://github.com/fyne-io/fyne)

## Prerequisites

``` sh
go mod init your-module-name
go get fyne.io/fyne/v2
```

Then, get the copy-pasted `main.go` from the [official repo](https://github.com/fyne-io/fyne).

## Run

``` sh
go run main.go
```

## Build

Windows

``` sh
go build -ldflags -H=windowsgui
```
