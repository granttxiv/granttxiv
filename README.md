```rust
#[derive(Debug)]
struct GrantXiv {
    role: Role,
    github: GitHub,
    email: Email,
    twitter: Twitter,
    tech_stack: Vec<Technology>,
}

impl SigridJinEth {
    fn new() -> Self {
        Self {
            role: Role::SoftwareEngineer,
            github: GitHub {
                username: "granttxiv".to_string(),
            },
            email: Email {
                address: "granttxiv@gmail.com".to_string(),
            },
            twitter: Twitter {
                handle: "granttxiv".to_string(),
            },
            tech_stack: vec![
                Technology::Python,
                Technology::Golang,
                Technology::TypeScript,
                Technology::Rust,
            ],
        }
    }
}

```
