
# CyberHub Module Registry

This repository contains the module list used by CyberHub Module Manager.

Checks are manual by default: open Module Manager and click **Check for updates**.
Core 1.5.0 also offers optional startup notification checks, disabled by default;
downloads and installation still require an explicit user action. Every package
is tied to a specific GitHub repository, release asset, file size and SHA-256 checksum.

The 5 November 2026 catalog updates Gallery to 1.3.1 with collapsible Collections
and a combined Tags tab for manual labels and optional AI results. The public
module ZIP was downloaded and its size/SHA-256 verified
before the catalog update. The other 15 module entries remain unchanged, including
Danbooru 1.0.1 and Upscaler 1.1.2-beta from the 15 October catalog.

## Channels and Publishers

- `official` identifies modules maintained by Cyberdelia.
- `community` identifies third-party modules accepted into the catalog.
- `stable` and `beta` describe release maturity independently from the publisher.

## Community Requests

Community modules may request inclusion through a GitHub issue. Inclusion in the list is not a security guarantee: Python modules contain executable code and users receive a warning before installing community code.
