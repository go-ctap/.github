# go-ctap

Go libraries and runtime components for working with FIDO2, CTAP, CTAPHID and platform WebAuthn APIs.

## Repositories

| Repository | Summary |
|---|---|
| [`kit`](https://github.com/go-ctap/kit) | Application-level CTAP/FIDO2 runtime for building CLI, GUI, and TUI tools around hardware token discovery, sessions, operations, interaction prompts, safety checks, and MDS lookup. |
| [`ctap`](https://github.com/go-ctap/ctap) | Core idiomatic Go CTAP/FIDO2 implementation. Provides layered APIs from raw CTAPHID transport and command client primitives up to higher-level authenticator workflows. |
| [`hid`](https://github.com/go-ctap/hid) | cgo-free Go HID library used as the low-level device access layer for CTAPHID/FIDO2 work. Covers enumeration, open, read, and write paths across supported platforms. |
| [`windows-proxy`](https://github.com/go-ctap/windows-proxy) | Windows service and named-pipe proxy that allows unprivileged applications to access FIDO2 HID tokens without running the whole application as administrator. |
| [`winhello`](https://github.com/go-ctap/winhello) | Go bindings for the Windows WebAuthn API / Windows Hello, including credential creation, assertions, platform credential management, extensions, and a helper for hidden window handles. |
