# b64min

A minimal base64 library.

**Add lib to deps:**

```toml
[libs.runtime]
b64min = { git = "https://github.com/shareui/b64min" }
```

**And import it:**

```yukino
load b64min: decode, encode

// encode(input: bytes) -> string
// decode(input: string) -> bytes
```

Just see the `b64min/lib.ykn`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 shareui.