# Personal Jailbreak Repo

[简体中文](./README.zh-CN.md)

Add via: [Source Homepage](https://locationovo.github.io/repo)

## Mirror Statement

This repository contains rebuilt and rewritten historical index mirrors:

- **Procursus**: rebuilt `iphoneos-arm64` indices for `1500`, `1600`, `1700`.
- **Bingner**: rewritten indices for `550.58`, `800.00`, `1200.00`, `1443.00`. Only the `Architecture` and `Filename` fields were remapped.

**Notes:**

1. Only index files (`Packages`, `Release`, etc.) are mirrored. No original `.deb` packages are stored or redistributed. Clients download directly from the official sources.
2. The `Architecture` field in the indices has been uniformly rewritten to `iphoneos-arm64`, intended for research use with modern package managers. Please evaluate compatibility before installing.

## Copyright

All third-party plugins and tools included in this repository are copyrighted by their original authors. For full license information, disclaimers, and contact details, see **[DISCLAIMER.md](./DISCLAIMER.md)**.