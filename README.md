# About

This exercise is from the section "Data Structures
That Power Your Database" from the book
_Designing Data-Intensive Applications_. It is
meant to illustrate an append-only log.

# How to use

In your terminal, run the following to load functions
from the file `log-structured-storage`.

```
source log-structured-storage.sh
```

The following functions are available:

```
db_set <key> <value>
db_get <key>
```
The data is stored in the `database` file. Key-value
pairs are separated by comma, and each pair is on
its own line.

# Examples

```
**db_set 42 '{"name":"San Francisco","attractions":["Golden Gate Bridge"]}'**
**db_get 42**
{"name":"San Francisco","attractions":["Golden Gate Bridge"]}
```
