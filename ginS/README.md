# Gin Default Server

This is API experiment for Gin.

```go
package main

import (
	"github.com/deepakgupta0212/gin1-7"
	"github.com/deepakgupta0212/gin1-7/ginS"
)

func main() {
	ginS.GET("/", func(c *gin.Context) { c.String(200, "Hello World") })
	ginS.Run()
}
```
