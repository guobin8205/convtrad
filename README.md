convtrad
=====

Convert from traditional chinese to simplified chinese.

## Install

	go get -u github.com/nadoo/convtrad

## Usage
```Go
package main

import (
	"fmt"

	"github.com/nadoo/convtrad"
)

func main() {
	fmt.Println(convtrad.ToSimp("劉德華abc"))
}
```
