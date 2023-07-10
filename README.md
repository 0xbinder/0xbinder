
```rust
struct Whoami {
    name: String,
    tech_stack: Vec<String>,
}

impl Whoami {
    fn new() -> Self {
        Whoami {
            name: String::from("QmVuamFtaW4="),
            tech_stack: vec![
                String::from("Android Engineer"),
                String::from("Security Researcher"),
                String::from("Kotlin"),
                String::from("Python"),
                String::from("Rust"),
                String::from("Flutter"),
            ],
        }
    }
}

```
