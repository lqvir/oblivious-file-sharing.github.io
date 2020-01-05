---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div align="center">
    <img src="assets/metal_logo.png" height="100" />
    
    <p style="margin-top: 20pt; font-size: 16pt;">Metal: A Metadata-Hiding File Sharing System</p>
</div>

## Research paper:
- Currently under minor revision. Full paper is in preparation.

## Code of the cryptographic building blocks:
- *libristretto-elgamal:* Rerandomizable encryption over Curve25519-Ristretto. [\[Code\]](https://github.com/oblivious-file-sharing/libristretto-elgamal) [\[Proof\]](https://github.com/oblivious-file-sharing/compact_elgamal_security_proof).
  * Extended from libristretto by [Mike Hamburg](https://www.shiftleft.org/) and [Tony Arcieri](https://tonyarcieri.com/).
- *obliv-c-ssl:* An extension to Obliv-C with TLS support. [\[Code\]](https://github.com/oblivious-file-sharing/obliv-c-ssl).
  * Modified from [Obliv-C](https://oblivc.org/) by Samee Zahur.
- *libpaillier-with-constant-time-dec:* Paillier encryption with constant-time decryption. [\[Code\]](https://github.com/oblivious-file-sharing/libpaillier-with-constant-time-dec)
  * Modified from [libpaillier](http://acsc.cs.utexas.edu/libpaillier/) by John Bethencourt.

## Protocol implementation:
- (To be released)