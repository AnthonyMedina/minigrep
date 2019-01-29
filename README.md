# minigrep

A miniature version of [grep](https://en.wikipedia.org/wiki/Grep) built in Rust with [The Rust Book](https://doc.rust-lang.org/book/ch12-00-an-io-project.html).

## Use

Search for all occurences of a string in a file:

```bash
cargo run <search_term> <file_name>
```

Case insensitive search:

```bash
CASE_INSENSITIVE=1 cargo run <search_term> <file_name>
```
