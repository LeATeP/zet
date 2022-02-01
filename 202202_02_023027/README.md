# golang pointers

* pointer to variable
1. if i use pointer 'i:=1'(p=&i) pointing at var 
1. i have to use '\*' read 'i' through pointer 'p' like so '\*p'

* point to type
1. there is no specific output problem with point to type
1. by creating type with pointer '&type' he creating just creating var as he is pointing to new type..
1. and can be used as usual... and the benefits is that you can give to any fn your var that point, the fn can change values in the pointer location.. which you can't do with any other var

