All variables in rust are immutable by default. A variable is declared with the following syntax:
```rust
let apples = 5; // immutable
```

To make a variable mutable, use the `mut` keyword
```rust
let mut kiwis = 4;
```

# References
You can reference a piece of data with `&`. They are immutable by default. To make a reference mutable, you must use `&mut`

```rust
let mut my_string = String::new();

// immutable reference to my_string
&my_string


// mutable reference to my_string
&mut my_string
```



# Naming Conventions
Rust standard naming conventions are to use snake_case for variable names.