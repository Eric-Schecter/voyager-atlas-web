# Voyager Atlas — Web Preview

[Open the preview](https://eric-schecter.github.io/voyager-atlas-web/)

This repository contains deployment configuration only. The Godot project source and its Git history are not included.

The exported website is attached to a versioned GitHub Release. The Pages workflow checks its SHA-256 checksum before publishing it. This avoids committing large game packages to Git or using Git LFS.

To publish an updated export, upload `site.zip` to a new Release, update `release.json` with the release tag and archive checksum, then run **Publish web preview** from the Actions tab.

The preview requires WebGL 2. Initial download is approximately 402 MiB; music starts after clicking to enter.
