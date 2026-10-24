# Vinci Work Releases

The public download and auto-update feed for Vinci Work. This repository holds
release artifacts; the application source is maintained separately.

## Download and update

- Download a published build from [Releases](https://github.com/getsimpledirect/vinci-work-releases/releases).
- Installed Vinci Work clients use this repository's `latest` release for updates.
- Read the selected release notes and its accompanying license notices before installing.

## Repository scope

This feed is a deployed consumer interface. Preserve release URLs, asset names
and the update channel while installed clients still use them. A small source
tree or infrequent commits do not make the feed redundant.

No source build or local test command is defined here. Application development,
artifact signing and release verification belong in the authorized Vinci Work
source/release workflow. A release listing alone does not prove that a download
or automatic update succeeds.

## Security and licensing

Release assets and public issues are public. Do not upload signing keys, provider
credentials, private user files or internal runtime captures.

[LICENSE](LICENSE) distinguishes original repository material from distributed
software. Authorized downloads and normal installation/use remain governed by
each artifact's accompanying terms. Upstream MIT, /ee Fair Source and other
third-party licenses remain applicable to their respective components.
