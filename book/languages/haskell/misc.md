# Interesting things about Haskell

* [**Galois**](https://galois.com/) is an active Haskell user.

* **Facebook** uses Haskell in several projects, including [Fighting spam with Haskell](https://code.fb.com/security/fighting-spam-with-haskell/)

* **Ericsson** uses Haskell for the implementation of [Feldspar](http://hackage.haskell.org/package/feldspar-compiler), an EDSL for digital signal processing algorithms.

* **Kaspersky** uses Haskell in it's antivirus software
  
## Haskell code compared to other languages

> Example of Hello World code in several languages.

### Haskell

```haskell
module Main where

main :: IO ()
main = putStrLn "Hello, World!"
```

### Golang

```golang
package main

import "fmt"

func main() {
    fmt.Println("Hello, World")
}
```

### Python

```Python
print "Hello world!"
```

### Ruby

```Ruby
puts "Hello world!"
```