## Nawaf

I build small web apps and automate my own machine.

### Projects

**[git-preflight](https://github.com/NawafIO/git-preflight)** · PowerShell

Scans a repository for secrets before you publish it — including the commit
history, where a secret you deleted is still sitting in an older blob. Every
match is redacted in the report, and if the scan cannot actually run it says so
loudly instead of returning a confident empty result.

**[windows-quick-clean](https://github.com/NawafIO/windows-quick-clean)** · PowerShell

A temp-file cleaner that reports before it removes anything. Deletion requires an
explicit flag, targets come from a fixed allowlist with no parameter to redirect
it, and every path is re-validated against a protected-root tripwire before a
single file is touched.

### Working with

- **Web** — HTML, CSS, JavaScript, Supabase (Postgres + Row Level Security)
- **Automation** — PowerShell on Windows
- **Scripting** — Python

### How I like to work

Ship small. Version control from the first commit. Row Level Security before the
first row. Secrets never touch the repo.

Both tools above document what they refuse to do, and what they cannot catch. I
would rather a tool of mine under-promise and be true.
