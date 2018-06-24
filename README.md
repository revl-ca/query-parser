# query-parser

Inspired from https://dev.mysql.com/doc/refman/5.7/en/expressions.html and https://github.com/justinkenel/js-sql-parse

## How to build

`yarn compile`

## How to test

`yarn test "foo = 'bar' && life = 42"`

## TODO

- [X] Multiple expr
- [X] String (single quote, double quote, backtick) 
- [X] Booleans
- [ ] IS [NOT]
- [ ] NOT expr
- [ ] ! expr
- [ ] bit_expr
- [ ] LIKE expr
- [ ] IN (expr)
- [ ] Date
