# PlugTrade releases

This repository holds only PlugTrade desktop release files. The source code is private.

Each release carries:

- `PlugTrade_X.Y.Z_x64-setup.exe`: the Windows installer
- `PlugTrade_X.Y.Z_x64-setup.exe.sig`: its update signature
- `latest.json`: the update feed

Installed copies of PlugTrade read `latest.json` of the newest release. When a newer version is
out, the app offers it in a dialog ("Update now" / "Later"). The installer is verified against
the signature before it runs.

Download PlugTrade at [plugtrade.io](https://plugtrade.io).
