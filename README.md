

```rust
 #[derive(Debug)]
enum Role {
    SoftwareEngineer,
}

#[derive(Debug)]
struct GitHub {
    username: String,
}

#[derive(Debug)]
struct Email {
    address: String,
}

#[derive(Debug)]
struct Twitter {
    handle: String,
}

#[derive(Debug)]
enum Technology {
    Python,
    Golang,
    TypeScript,
    Rust,
}


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
