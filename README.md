### GPG public key reppsitory
Since the SKS keyservers are down and keys.openpgp.org is complete useless, at least in my application use case because I need the third-party-signatures for some reasons, I decided to host my GnuPG public keys on github.

### Usage
After cloning this repository simply execute the key-update.sh script. This pulls the latest version of this repository from GitHub and imports the updated keys (if neccessary).
