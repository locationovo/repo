# Personal Jailbreak Repo

[中文文档](./README.zh-CN.md)

Add via: [Source Homepage](https://locationovo.github.io/repo)

## Overview

This repository is an automated jailbreak source hosted on GitHub Pages. It aggregates packages distributed as assets in GitHub Releases from various sub-repositories.

### Architecture

- **Main Repository (this repo)**: Hosts the index and signatures. It fetches metadata from Releases via GitHub API.
- **Recipes**: Builds custom packages from source and uploads `.deb` files to Releases.
- **Patched Legacy**: Patches legacy rootful packages for modern environments and uploads them to Releases.

**Notes:**

1. **No `.deb` files are stored directly in this Git repository.** Packages are hosted as GitHub Release assets and downloaded via their CDN.
2. Legacy packages are patched using `rootless-patcher`. If patching fails or crashes, the original package is distributed. Compatibility is not guaranteed; please evaluate before installing.

## Copyright

All third-party plugins and tools included in this repository are copyrighted by their original authors. For full license information, disclaimers, and contact details, see **[DISCLAIMER.md](./DISCLAIMER.md)**.