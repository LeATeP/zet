# css display: flex elements explained


- display: flex?
set to sort elements to flex

- flex-direction: row/column
abject element position where he will point to

- justify-content: flex/normal
abject by moving from and to element from position of object point to
with 'flex-direction'

- align-items: default stretch
abject by moving left and right element from position of object point to
with 'flex-direction'

- align-self: flex/normal
align specific item inside main 'align-items' or 'display'

- flex: is a shorthand property of
`flex-grow`, `flex-shrink`, `flex-basis` 
    1. flex: 1;       the same as 1 1 auto # if 2 then 2 1 auto
    1. flex: initial; the same as 0 1 auto
    1. flex: auto;    the same as 1 1 auto
    1. flex: none;    the same as 0 0 auto

- flex-grow: 0 default (*growth factor) 
make an object to fill available space in the direction where object
point to with 'flex-direction'

- flex-shrink: 1 default (*shrink factor)
the same as `grow` but opposite, object will shrink only when container
is too small to fit. or refuse to shrink with 0 value

- flex-basis: set initial size of flex item, default `auto`

- gap: default 0
add space between flex items, much like padding