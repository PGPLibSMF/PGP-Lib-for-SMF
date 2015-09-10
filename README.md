OpenPGP.php: OpenPGP for PHP
============================

This is a pure-PHP implementation of the OpenPGP Message Format (RFC 4880).

* <https://github.com/PGPLibSMF/PGP-Lib-for-SMF/>

### About OpenPGP

OpenPGP is the most widely-used e-mail encryption standard in the world. It
is defined by the OpenPGP Working Group of the Internet Engineering Task
Force (IETF) Proposed Standard RFC 4880. The OpenPGP standard was originally
derived from PGP (Pretty Good Privacy), first created by Phil Zimmermann in
1991.

* <http://tools.ietf.org/html/rfc4880>
* <http://www.openpgp.org/>

Features
--------

* Encodes and decodes ASCII-armored OpenPGP messages.
* Parses OpenPGP messages into their constituent packets.
  * Supports both old-format (PGP 2.6.x) and new-format (RFC 4880) packets.
* Helper class for verifying, signing, encrypting, and decrypting messages using Crypt_RSA from <http://phpseclib.sourceforge.net>
* Helper class for encrypting and decrypting messages and keys using Crypt_AES and Crypt_TripleDES from <http://phpseclib.sourceforge.net>

Users
-----

OpenPGP.php is currently being used in the following projects:

* <http://drupal.org/project/openpgp>

