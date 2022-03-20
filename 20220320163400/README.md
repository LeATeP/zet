# go interface

a interface can hold any value that implement those methods

to implement interface

```go
type rec int
type a interface {
	fn int
}
```
first is a need of `rec` type, that has method of `fn` which return int

interface is just getting `rec` by packaging him in his own type

if there is a need in `a` interface, then it's brief description of what methods a type `rec` have at his disposal, and what they doing

```go
r := rec(1)
var inter a
a = r
r.fn()
```
