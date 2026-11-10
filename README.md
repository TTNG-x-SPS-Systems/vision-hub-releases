# Vision Hub — releases

Release builds of the **Vision Hub** WordPress plugin, which runs on the
central TTNG hub site only. This repo holds nothing but releases: the
plugin's source is in a private repo.

The hub checks here for updates automatically and offers them in
**Dashboard → Updates**. Each release has two assets: `vision-hub.zip`, the
plugin the hub installs, and `vision-hub.json`, the update file it reads.

To install by hand, download `vision-hub.zip` from the
[latest release](../../releases/latest) and upload it in
**Plugins → Add New → Upload Plugin**. Never install it on a member site.

Releases are published by the source repo's `bin/release.sh`. Don't commit
anything else here, and don't attach other files to a release.
