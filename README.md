# YD Home iframe QA

Public, static GitHub Pages harness for testing the Magic Cabinet YD Home embed from a genuine third-party HTTPS parent origin.

Default target:

`https://app.magiccabinetai.com/design/ydhome?embed=1&qa=github`

The iframe uses the same documented sandbox capabilities used by the Wix embed test:

`allow-scripts allow-same-origin allow-forms allow-popups allow-pointer-lock`

Override the target with `?target=<https-url>` when testing another deployed Magic Cabinet environment.

No API keys, credentials, user data, or application code are stored in this repository.
