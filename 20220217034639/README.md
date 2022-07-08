# thoughts about go/python

The problem with go, is that it's not very good at network/sql/sleep
it's more about high performance, high calculation, ML/algoritms 
that req processing power and multi-threading

making socket/sql handlers is good, and i should standartizing it for python/go 
in separate template repos

* go should be really good as a serve
so as long as i have little code to compute and only executing sql query's, or sleep... 
python will outperforme

python is great for interface, for direct cmd's
where as go is only for running inside containers, and responsible for infrastructure



-- go advance method to query database
by query a single row, no need query everything all at once
can be itered by row count
```go
QueryRow(string, ...interface{}) *sql.Row
```
