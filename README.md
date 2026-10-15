# Panel Remapper updates

The signed update files of the Panel Remapper, and `latest.json`, which names the newest. Nothing else: no code and
no mapping data (the project itself is the private repository `haugdal/panel-remapper`).

Every installed Panel Remapper looks here by itself (Panel Remapper menu → Check for Updates…, and on its own every
six hours) at `https://raw.githubusercontent.com/haugdal/panel-remapper-updates/main`. It installs a file only when
its signature is the maker's, so this repository being public lets no one else push an update.

Files are added by `installer/push-update.sh` in the Panel Remapper project; do not edit them by hand.
