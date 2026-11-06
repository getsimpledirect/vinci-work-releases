# Vinci Work Releases

The public download and update feed for Vinci Work, whose desktop application
is branded **Vinci Desktop**. This repository holds release artifacts; the
application source is maintained separately.

## Download and update

- Download a published build from [Releases](https://github.com/getsimpledirect/vinci-work-releases/releases).
- Read the selected release's notes, platform/architecture, and accompanying
  license notices before installing. The macOS distribution uses DMG and ZIP
  assets; an update also needs the matching `latest-mac.yml` feed metadata.
- Packaged clients on the **stable** channel use the repository's
  [`latest` release](https://github.com/getsimpledirect/vinci-work-releases/releases/latest).
  A prerelease can be downloaded from its release page without becoming the
  stable updater target.
- The macOS **alpha** channel uses the separate `alpha-macos-latest` feed.
  A channel's presence in the client does not establish that a build is
  currently published there.

Update checks, downloads, and installation are separate steps. Current clients
reject ordinary downgrades. Follow the selected build's instructions and
confirm the installed version after an update.

## Repository scope

This feed is a deployed consumer interface. Preserve release URLs, asset names,
feed metadata, and update channels while installed clients still use them.
A small source tree or infrequent commits do not make the feed redundant.

No source build or local test command is defined here. Application development,
artifact signing, notarization, and release verification belong in the
authorized Vinci Work source/release workflow. Unsigned internal CI artifacts
are a separate distribution path. A release listing alone does not prove that
a download or automatic update succeeds, or that it includes every change in
the source repository.

For help, use [Vinci support](https://vinci.getsimpledirect.com/support?source=work).
Include the installed version, operating system, expected behavior, and a
minimal reproduction without private files or credentials.

## Security and licensing

Release assets and public issues are public. Do not upload signing keys,
provider credentials, private user files, or internal runtime captures.

[LICENSE](LICENSE) distinguishes original repository material from distributed
software. Authorized downloads and normal installation/use remain governed by
each artifact's accompanying terms. Upstream MIT, /ee Fair Source, and other
third-party licenses remain applicable to their respective components.
