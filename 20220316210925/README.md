# go methods

build function to call by struct
method is a func with receiver argument

```go
type num struct {
	rand int
}

func main() {
	n := num{rand: 0}
	rand.Seed(time.Now().Unix())

	n.random()
	fmt.Println(n.rand)
}

func (n *num) random() {
n.rand = int(rand.Int31n(1000))
}
```
