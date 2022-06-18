# css display: flex elements explained


- display: flex?
set to sort elements to flex

- flex-direction: row/column
abject element position where he will point to

- justify-content: flex/normal
abject by moving from and to element from position of object point to
with 'flex-direction'

- align-items: flex/normal
abject by moving left and right element from position of object point to
with 'flex-direction'

- align-self: flex/normal
align specific item inside main 'align-items' or 'display'

- flex: is a shorthand property of
`flex-grow`, `flex-shrink`, `flex-basis` when the value is 1, its
apply as `1 1 0%`

- flex-grow: 0 default (*growth factor) 
make an object to fill available space in the direction where object
point to with 'flex-direction'

- flex-shrink: 1 default (*shrink factor)
the same as `grow` but opposite, object will shrink only when container
is too small to fit. or refuse to shrink with 0 value

- flex-basis: set initial size of flex item, default `auto`