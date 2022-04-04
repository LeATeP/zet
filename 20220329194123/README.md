# vaava net code system

## server side
msg consist of {codeId, name, num}, 
- Id saying what purpose is the msg
- Name is object name to append
- number value, or amount the object have

`0` or default, meaning no msg, error or something
`1` connection ping to verify to client that server is alive
`2` getting info about client
`3` notify client about server changes
`4` client saying that he is shutting down
`5` client saying that he is reloading
`6` sending specific data, say appending to map.

## client side

`0` or default, no msg, server is shut, error or something
`1` connection ping to verify to server that client is alive
`2` getting info about server
`3` signal to change settings to...
`4` signal to shutdown
`5` signal to reload




