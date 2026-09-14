# YD Home iframe QA

Public, static GitHub Pages harness for testing the Magic Cabinet YD Home embed from a genuine third-party HTTPS parent origin.

Default target:

`https://suppliers-legs-predict-mail.trycloudflare.com/design/ydhome?embed=1&qa=github`

The iframe uses the same documented sandbox capabilities used by the Wix embed test:

`allow-scripts allow-same-origin allow-forms allow-popups allow-pointer-lock`

This September 14 preview serves the isolated `magic-cabinet-mvp-iframe-release` worktree on local port 4173. It uses the real Clerk test application and proxies API requests to the existing development API. No dev web deployment or Wix changes are part of this preview. It is not production login, pricing approval, PDF delivery, or multi-store acceptance evidence.

To change the target, update both the iframe and full-page link in `index.html` through a pull request to `gh-pages`.

No API keys, credentials, user data, or application code are stored in this repository.

This Cloudflare quick-tunnel target is ephemeral and remains available only while the local preview/tunnel process is running.
