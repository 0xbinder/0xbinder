
```rust
struct Whoami {
    name: String,
    tech_stack: Vec<String>,
}

impl Whoami {
    fn new() -> Self {
        Whoami {
            name: base64::decode("QmVuamFtaW4="),
            tech_stack: vec![
                String::from("Android Engineer"),
                String::from("Security Researcher"),
                String::from("Python"),
                String::from("Rust")
            ],
        }
    }
}

```
