# What is Golo?

Golo source code need to be placed in modules. Module names are separated with dots, as in:

```golo
Foo
foo.Bar
foo.bar.Baz
(...)
```
A Golo module can be executable if it has a function named main and that takes an argument for the JVM program arguments:

```golo
module hello.World

function main = |args| {
  println("Hello world!")
}
```

?[On which kind of entity, golo code must be set? ](single)
- [] Package
- [] Class
- [x] Module
- [x] Structure
