# ReviTel desktop releases

Installers of the ReviTel desktop app for Windows and macOS. Binaries only: the source is private.

The app downloads updates from here through ReviTel's release list and installs one only when its SHA-256 matches and its
Ed25519 signature is valid for ReviTel's release key. Each release carries the installer, a  file and a  file.

macOS builds are signed and notarized (Developer ID, LEGASUM LTD). Windows builds are not Authenticode-signed yet.

## ReviTel release key (Ed25519, SPKI)

```
-----BEGIN PUBLIC KEY-----
MCowBQYDK2VwAyEAoaHc14yliasKrwuBxTjsyVY94fDi62dsaF48dwzcn3o=
-----END PUBLIC KEY-----
```

Made by Revixon. Calls are never recorded.
