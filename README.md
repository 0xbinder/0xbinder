```rust
struct Whoami {
    name: String,
    tech_stack: Vec<String>,
}

impl Whoami {
    fn new() -> Self {
        Whoami {
            name: String::from("pl4int3xt"),
            tech_stack: vec![
                String::from("Android Dev and Hacking"),
                String::from("CTF player @p3rf3ctr00t"),
                String::from("Binary exploitation")
            ],
        }
    }
}
```
