There are many functions in std. 

#### read_line()
```rust
std::io:stdin().read_line(&mut guess);


// or with import
use std:io;
io::stdin().read_line(&mut guess);
```

`read_line` *appends* the contents of the user input in stdin to the string passed as a parameter. It does not overwrite. 

`read_line` returns a `Result` which is an enum. Possible states of enum are called "variant". `Result`'s variants are `Ok` and `Err`. 

Calling `.expect(msg)` on a Result will throw an error with the message if the Result is an `Err`, and it will take the return value that `Ok` is holding and return it to you so you can use it. For `read_line`, that is the number of bytes in the input.  