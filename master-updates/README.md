# PetCompanion Master update feed

This feed is separate from regular PetCompanion releases. Source stays private.

The initial 1.21.1-master.2 installer is supplied directly to Rosetta. This baseline has no installer assets: there is no newer Master update to offer yet. Only the same currently installed version can report current from this baseline. Empty file lists are never offered as installable updates.

For each future Master update, publish the matching Master installer under tag `v<version>` first, verify its download and SHA-512, then replace `master.yml` with metadata generated from that installer. The version must be `x.y.z-master.n`, and its single file must be `PetCompanion-Master-Setup-<version>-x64.exe` in that version's release. Do not point this feed at a regular or Preview installer. Do not upload private source here.

Installed Masters ask separately before download and installation. Manual setup finishes the installation and reopens Master. Master saves and inspection controls stay separate.
