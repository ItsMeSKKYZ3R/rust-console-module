# Example for the clear_after function
---
### For use this function, import the module as precise in the README.md file and write it in your file
```rs
// Import the module

mod console;
use std::time;

fn main() {
    let duration = time::Duration::from_millis(10);

    console::clear_after(duration);
}
```