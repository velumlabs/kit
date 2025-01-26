# **Velum Kit**
![Velo (2)](https://github.com/user-attachments/assets/ccd20321-723c-4126-b115-941310adf81e)

A dual-language package (Go/Rust) for building and managing LLM function calling tools and toolkits. Built specifically for Thor.

# **Features**
- Abstract Tool interface for implementing LLM-compatible functions
- Default tool implementation with required metadata
- Toolkit management for grouping related tools
- Functional options pattern for configuration (Go)
- Builder pattern for configuration (Rust)
- JSON schema support for function parameters and returns

# **Installation**

**Go**

```go get github.com/velumlabs/kit/go```


**Rust**
```
toolkit = { git = "https://github.com/velumlabs/kit", subdirectory = "rust" }
```

# **Usage**
Both implementations provide similar functionality with language-specific idioms:

- Go uses the functional options pattern for configuration
- Rust uses the builder pattern for configuration
- Both support async execution of tools
- Both use JSON schemas for parameter and return type definitions

For examples, see the language-specific directories:

- Go examples in go/examples
- Rust examples in rust/examples
