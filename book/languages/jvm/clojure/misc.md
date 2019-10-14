# Interesting facts about Clojure

## Clojure code compared to other languages

> Example of Hello World app in some languages

### Clojure

```clojure
(ns clojure.examples.hello
  (:gen-class))
(defn hello-world []
  (println "Hello World"))
(hello-world)
```

### Java

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Ruby

```Ruby
puts "Hello world!"
```
