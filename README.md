# ReplayLabb Downloads

ReplayLabb is a desktop tool for recording and investigating API traffic from apps you connect to it. This repository contains official test downloads. The application source is maintained separately.

## Get the test build

Download [ReplayLabb 0.1.0 Test 1](https://github.com/Dixon-O/replaylabb/releases/tag/v0.1.0-test.1).

| Platform | Download |
| --- | --- |
| Windows x64 | Choose the setup EXE for a standard installation, or the MSI if you need Windows Installer. The standalone EXE skips the installer and requires WebView2 to be available. |
| Ubuntu 24.04 x64 | Download the `.deb` and install it with `sudo apt install ./ReplayLabb-0.1.0-bb5269b-linux-x64.deb` from the download folder. APT can fetch the declared runtime dependencies. |
| macOS (Intel and Apple Silicon) | Pending |
| Windows ARM64 and Linux ARM64 | Pending |

The Windows files are unsigned, so Windows may show an unknown-publisher warning. These builds are intended for testing, and clean-machine installation is still being verified. Each release includes `SHA256SUMS` so you can check the downloaded files.

When reporting a problem, include the release version, your OS version, and whether your device is x64 or ARM64. Remove credentials and private traffic from any logs you share.
