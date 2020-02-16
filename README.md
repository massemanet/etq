# etq
Erlang Term Query

A pipe program for querying Erlang Terms (similar in spirit to `jq`).

Usage;
```shell
$ echo "[a,#{foo=>{a,b}},c]" | ./bin/etq 2.foo.2
b
```
