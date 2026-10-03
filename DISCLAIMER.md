# Third-Party Plugin Disclaimer and Notice

[简体中文](./DISCLAIMER.zh-CN.md)

## About This Repository

This repository is an automated jailbreak repository hosted on GitHub Pages. It synchronizes plugin indices from multiple public jailbreak sources via GitHub Actions.

## Third-Party Plugin Copyright Notice

This repository indexes and distributes plugin packages from various third-party jailbreak sources. All copyrights for these plugins belong to their original authors. This project only performs the following operations:

- **Index Mirrors (e.g., Procursus, Bingner)**: Only the `Packages` indices are synchronized and converted (the `Architecture` field is rewritten to `iphoneos-arm64` or `arm64`, and `Filename` is pointed to the original official servers). **No `.deb` packages are physically stored or redistributed.** Clients download directly from the original official sources.
- **Main and Auxiliary Repositories**: The original architectures of the plugins are preserved (e.g., `iphoneos-arm64`, `iphoneos-arm64e`). Only index merging and deduplication are performed, without modifying the original packages.

The following notices apply to third-party plugins under different license types:

### 1. Permissive Licenses (MIT/BSD/Apache 2.0)

Such plugins allow free use, copying, modification, and redistribution, provided that the original copyright notice is retained. This project retains the original author, version, and license information in the indices. If you are a plugin author and find any information inaccurate or wish to adjust how it is presented, please contact us.

### 2. Copyleft Licenses (GPL/LGPL)

Such plugins require that the complete source code be provided upon redistribution, and that derivative works be released under the same license. This project only modifies index metadata and does not modify the plugin code itself. If you believe this repository's redistribution method does not comply with GPL requirements, please let us know, and we will immediately provide source code links or remove the relevant entries.

### 3. Plugins Without an Explicit License

Some older plugins do not include an explicit license file. Under copyright law, the absence of a license means "all rights reserved." This project includes such plugins solely for **compatibility adaptation and archival purposes**, with no intention of infringing upon the original authors' rights. If you are the rights holder of such a plugin and do not wish for it to be indexed or distributed in this repository, please contact us using the details below, and we will remove the relevant content within **48 hours** of receiving notice.

### 4. Plugins Explicitly Prohibiting Redistribution

If you find that this repository has inadvertently included a plugin explicitly marked as "redistribution prohibited," this is an oversight in the review process. Please contact us immediately, and we will delete the relevant entries and all associated files within **24 hours**.

## Self-Modified and Rebuilt Tools

This repository additionally includes some classic open-source tools (e.g., Git, FFmpeg) that have been modified and rebuilt to adapt to the jailbreak environment or supplement specific features. Unlike the aforementioned plugins that only undergo architecture adaptation, these tools **involve substantive modifications to the source code and recompilation**.

The following principles apply to such tools:

### 1. License Compliance

The modified tools continue to be distributed under the original project's open-source license (e.g., GPL, LGPL). Each tool package includes:
- The original copyright notice and full license text
- The upstream project repository link
- The complete modified source code repository link (publicly accessible)

If the original project uses a strong copyleft license such as GPL, the modified source code has been fully disclosed under the same license in the corresponding repository, ensuring that recipients enjoy the same freedoms.

### 2. Scope of Modification

Modifications are limited to jailbreak environment compatibility adaptation, bug fixes, or feature enhancements. No ads, malicious code, or backdoors are introduced. Detailed modification records for each tool can be viewed in the commit history of its source repository.

### 3. Copyright Ownership

The original copyrights of these tools remain with the original authors. This repository only holds rights to the modified portions and distributes them under the terms of the original project's license. The copyright notice files in the tool packages clearly distinguish between the original authors and the modifier.

## Disclaimer

- This project provides all third-party plugin indices and adaptation information on an "as-is" basis, **without any express or implied warranties** regarding their functionality, security, stability, or legality.
- The risk of using third-party plugins is borne solely by the user. The maintainers of this project assume no responsibility for any device damage, data loss, system anomalies, or other losses caused by installing or using plugins indexed or distributed by this repository.
- This project does not make a final judgment on the license compliance of third-party plugins. Users should verify the original license terms themselves before use.
- All trademarks, product names, and logos in this repository are the property of their respective owners and are used for identification purposes only.

## Copyright Complaints and Contact

If you are the copyright owner of a relevant plugin and have any objections to how it is included in this repository, please contact us via:

- **Email:** [locationovo@outlook.com]
- **GitHub Issue:** [locationovo/repo]

Please provide the following in your email or Issue:
1. The name and version of the infringing plugin
2. Your proof of copyright or statement of authorship
3. The action you wish us to take (removal, attribution modification, license supplementation, etc.)

We will handle valid notices as quickly as possible.