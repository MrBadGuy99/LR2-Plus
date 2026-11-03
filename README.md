# LR2 Plus

LR2 Plus is a mod for LEGO Racers 2 (2001, PC): online and splitscreen lobbies, upgrade points and car stats, energy
weapons, smarter CPU drivers, weather and evening skies, and more. This repository only holds the releases. The mod's
launcher (v92 and later) checks here each time it opens and offers each new release. Every release's files are listed
in `manifest.txt` with their sizes and SHA-512 hashes, and `manifest.txt` is signed (`manifest.sig`, Ed25519), so the
launcher installs nothing that wasn't signed with the LR2 Plus key. Updates never touch your settings, profiles,
friends, controls or saves; the replaced files are kept in `Archive\DLL backups`.

Signing key (public): `7fe606106a413184c48a6e606ca7aba4f2d5b1cedd21774f51c416271ae7561d`
