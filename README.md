# Canopy updates

Where Canopy's releases are published: the disk image to download, and the update list Canopy Updater reads
(`updates.json`), with each release's zip beside it. Served by GitHub Pages at
https://quadricanna.github.io/canopy-updates/.

Every entry in `updates.json` carries an Ed25519 signature made with the maker's key, and Canopy Updater installs a
release only if its size, SHA-256, signature and developer team all match. Nothing here is code.
