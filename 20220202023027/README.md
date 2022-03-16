# golang pointers

* pointer to variable
1. if i use pointer 'i:=1'(p=&i) pointing at var 
1. i have to use '\*' read 'i' through pointer 'p' like so '\*p'

* point to type
1. there is no specific output problem with point to type
1. by creating type with pointer '&type' he creating just creating var as he is pointing to new type..
1. and can be used as usual... and the benefits is that you can give to any fn your var that point, the fn can change values in the pointer location.. which you can't do with any other var


## pointers with slice
point is not needed in case of only changing value of existing value in a slice
actions that req assigning new slice like "append", req pointer

## pointers to map
point in not needed in any case

## point to a struct
work the same with any value, if value stored in stuct slice or map, take referrence above

each value in a struct working as they intendent, and there is no additional function added in type/struct

if you want to completely change the value, to add completely new slice or map, req pointer to this slot of struct


## links
[Go Blog: Mechanics of 'append'][mechanics-of-append]

[mechanics-of-append]: https://go.dev/blog/slices
