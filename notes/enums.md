Rust has enums like most languages do. 

In Rust, possible values of an enum are called `Variants`.


## Common Enums

#### `Result`
`Result` has 2 variants, `Ok` and `Err`

###### What uses it?
- `std::io::stdin().read_line()`


#### Ordering
`Ordering` has 3 variants, `Less`, `Greater`, and `Equal`

###### What uses it?
- `my_string.cmp`