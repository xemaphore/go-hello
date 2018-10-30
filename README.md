# Hello World in Go
A simple go package with only one function named "Message" that write "Hello, World!" into standard output.

First install package with following command:

```bash
go get github.com/xemaphore/go-hello
```

Then you can use it like:

```go
package main

import "github.com/xemaphore/go-hello"

func main() {
    hello.Message()
}
```
