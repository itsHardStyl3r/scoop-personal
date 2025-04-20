# Personal Scoop Bucket

[![Tests](https://github.com/itsHardStyl3r/scoop-personal/actions/workflows/ci.yml/badge.svg)](https://github.com/itsHardStyl3r/scoop-personal/actions/workflows/ci.yml) [![Excavator](https://github.com/itsHardStyl3r/scoop-personal/actions/workflows/excavator.yml/badge.svg)](https://github.com/itsHardStyl3r/scoop-personal/actions/workflows/excavator.yml)

My personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer. For manifests that I need updated.

## Current improvements

* qbittorrent: Added file associations for .torrent and .magnet
  files. (https://github.com/ScoopInstaller/Extras/pull/14839)
* virtualbox-with-extension-pack-np: Fixed extension pack holding up the updates and updated the manifest.
* virtualbox-with-extension-pack-np: Extension pack is now installed automatically.
* zerotier-np: Updated checkver regex so it updates work correctly.

## Imports from other buckets

* qbittorrent from [ScoopInstaller/Extras](https://github.com/ScoopInstaller/Extras)
* virtualbox-with-extension-pack-np from [ScoopInstaller/Nonportable](https://github.com/ScoopInstaller/Nonportable)
* zerotier-np from [ScoopInstaller/Nonportable](https://github.com/ScoopInstaller/Nonportable)

## How do I install these manifests?

To add this bucket, run

```pwsh
scoop bucket add hardstyl3r https://github.com/itsHardStyl3r/scoop-personal
```

To install, do

```pwsh
scoop install hardstyl3r/<manifestname>
```
