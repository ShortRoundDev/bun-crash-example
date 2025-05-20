# bun-crash

Reproduction steps:

1. run `bun ./index.html`

2. Go to `localhost:3000` in a web browser

3. Open `template.html` in a code editor

4. Change some text within `template.html` and save the file

Then bun will crash:

```
============================================================
Bun v1.2.13 (64ed68c9) Windows x64
Windows v.win11_dt
CPU: sse42 avx avx2
Args: "C:\Users\[username]\.bun\bin\bun.exe" ".\index.html"
Features: Bun.stdin(2) http_server jsc dev_server tsconfig 
Elapsed: 252247ms | User: 218ms | Sys: 281ms
RSS: 0.17GB | Peak: 0.20GB | Commit: 0.23GB | Faults: 89312

panic(main thread): Internal assertion failure
oh no: Bun has crashed. This indicates a bug in Bun, not your code.

To send a redacted crash report to Bun's team,
please file a GitHub issue using the link below:
```