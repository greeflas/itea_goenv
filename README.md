# ITEA Goenv

This is example of Go library for Golang course in IT Education Academy.

## Installation

```shell
go get github.com/greeflas/itea_goenv
```

## Usage

```golang
package main

import goenv "github.com/greeflas/itea_goenv"

func main() {
	if err := goenv.LoadEnv("./.env"); err != nil {
		panic(err)
    }
}
```
