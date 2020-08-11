# its350
course materials and references for its350

## module04 Authentication & Norepudiation

* __Message Authentication Code__
  * [Man-in-the-middle attack](https://en.wikipedia.org/wiki/Man-in-the-middle\_attack)
  * [Message authentication](https://en.wikipedia.org/wiki/Message\_authentication)
  * [Message authentication code](https://en.wikipedia.org/wiki/Message\_authentication\_code)
    * [openssl-mac](https://www.openssl.org/docs/manmaster/man1/openssl-mac.html)
  * [HMAC](https://en.wikipedia.org/wiki/HMAC)
    * [Using openssl to generate HMAC using a binary key](http://nwsmith.blogspot.com/2012/07/using-openssl-to-generate-hmac-using.html)
    * [Openssl Command Line Utilities](https://wiki.openssl.org/index.php/Command\_Line\_Utilities)
  * [openssl: recover key and IV by passphrase](https://security.stackexchange.com/questions/29106/openssl-recover-key-and-iv-by-passphrase)
  * [openssl: EVP_BytesToKey](https://www.openssl.org/docs/manmaster/man3/EVP\_BytesToKey.html)
    

* __Digital Signatures__
  * [Digital signature](https://en.wikipedia.org/wiki/Digital\_signature)
    * [RSA sign and verify using Openssl : Behind the scene](https://medium.com/@bn121rajesh/rsa-sign-and-verify-using-openssl-behind-the-scene-bf3cac0aade2)
  * [Digital Signature Algorithm](https://en.wikipedia.org/wiki/Digital\_Signature\_Algorithm)

* __Public Key Infrastructure__
  * [Public key infrastructure](https://en.wikipedia.org/wiki/Public\_key\_infrastructure)
    * [Public key certificate](https://en.wikipedia.org/wiki/Public_key_certificate)
      * [Authorization certificate](https://en.wikipedia.org/wiki/Authorization\_certificate)
      * [Root certificate](https://en.wikipedia.org/wiki/Root\_certificate)
      * [Chain of trust](https://en.wikipedia.org/wiki/Chain\_of\_trust)
      * [Self-signed certificate](https://en.wikipedia.org/wiki/Self-signed\_certificate)
    * [X.509](https://en.wikipedia.org/wiki/X.509)
      * [ASN.1](https://en.wikipedia.org/wiki/ASN.1)
    * [Public key fingerprint](https://en.wikipedia.org/wiki/Public\_key\_fingerprint)
    * [Online Certificate Status Protocol](https://en.wikipedia.org/wiki/Online\_Certificate\_Status\_Protocol)
    * [Certificate authority](https://en.wikipedia.org/wiki/Certificate\_authority)
      * [Let's Encrypt](https://en.wikipedia.org/wiki/Let%27s\_Encrypt)
      * [Let's Encrypt](https://letsencrypt.org/)
    * _Practices_
      * [The Most Common OpenSSL Commands](https://www.sslshopper.com/article-most-common-openssl-commands.html)
      * [OpenSSL command cheatsheet](https://www.freecodecamp.org/news/openssl-command-cheatsheet-b441be1e8c4a/)
      * [x509 command](https://www.openssl.org/docs/man1.0.2/man1/x509.html)
  * [Key server (cryptographic)](https://en.wikipedia.org/wiki/Key\_server\_\(cryptographic\))
    * [PGP Global Directory](https://keyserver.pgp.com)
    * [sks-keyservers](https://sks-keyservers.net/)
      * [SKS Keyserver source code](https://github.com/SKS-Keyserver/sks-keyserver)
    * [Hockeypuck OpenPGP keyserver](https://keyserver.ubuntu.com/)
    * [PGP Public Key Server](https://pgp.key-server.io/)
    * [MIT PGP Public Key Server](https://pgp.mit.edu/)
  * [The GNU Privacy Handbook](https://www.gnupg.org/gph/en/manual/book1.html)



* __Authentication__
  * [Authentication](https://en.wikipedia.org/wiki/Authentication)
    * [Multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor\_authentication)
      * [BoilerKey Two-Factor Authentication](https://www.purdue.edu/securepurdue/identity-access/boilerkey/index.php)
      * [FIDO Alliance](https://en.wikipedia.org/wiki/FIDO\_Alliance)
        * [FIDO Alliance](https://fidoalliance.org/)
        * [How FIDO Works](https://fidoalliance.org/how-fido-works/)
        * [FIDO Alliance specifications](https://fidoalliance.org/specifications/download/)
    * [Strong authentication](https://en.wikipedia.org/wiki/Strong\_authentication)
    * [Passwd](https://en.wikipedia.org/wiki/Passwd)
      * [Salt (cryptography)](https://en.wikipedia.org/wiki/Salt\_\(cryptography\))
      * [crypt (C)](https://en.wikipedia.org/wiki/Crypt\_\(C\))
      * [Password cracking](https://en.wikipedia.org/wiki/Password\_cracking)
        * [Example hashes of passwords](https://hashcat.net/wiki/doku.php?id=example\_hashes)
        * [LM, NTLM, Net-NTLMv2, oh my! A Pentester’s Guide to Windows Hashes](https://medium.com/@petergombos/lm-ntlm-net-ntlmv2-oh-my-a9b235c58ed4)
        * [Crack­ing Win­dows 10 Account Pass­word: Is it Still Pos­si­ble? How to Pre­vent it?](https://www.guidingtech.com/61991/cracking-windows-10-password-prevent/)
      * [Security Account Manager](https://en.wikipedia.org/wiki/Security\_Account\_Manager)
    * [Smart card](https://en.wikipedia.org/wiki/Smart\_card)
      * [List of smart cards](https://en.wikipedia.org/wiki/List\_of\_smart\_cards)
      * [Contactless smart card](https://en.wikipedia.org/wiki/Contactless\_smart\_card)
      * [Contactless payment](https://en.wikipedia.org/wiki/Contactless\_payment)
      * [Mobile payment](https://en.wikipedia.org/wiki/Mobile\_payment)
        * [Google Pay](https://en.wikipedia.org/wiki/Google\_Pay)
    * [Magnetic stripe card](https://en.wikipedia.org/wiki/Magnetic\_stripe\_card)
    * [Telephone card](https://en.wikipedia.org/wiki/Telephone\_card)
    * [Electronic identification](https://en.wikipedia.org/wiki/Electronic\_identification)
      * [Electronic signature](https://en.wikipedia.org/wiki/Electronic\_signature)
      * [Extended Access Control](https://en.wikipedia.org/wiki/Extended\_Access\_Control)
        * [OpenPACE](https://frankmorgner.github.io/openpace/)
        * [Password Authenticated Connection Establishment with the Internet Key Exchange Protocol version 2 (IKEv2)](https://tools.ietf.org/html/rfc6631)
    * [Identity document](https://en.wikipedia.org/wiki/Identity\_document)
      * [ISO/IEC 7810](https://en.wikipedia.org/wiki/ISO/IEC\_7810)
    * [Biometrics](https://en.wikipedia.org/wiki/Biometrics)
      * [Biometric device](https://en.wikipedia.org/wiki/Biometric\_device)
      * [Biometric passport](https://en.wikipedia.org/wiki/Biometric\_passport)
      * [Biometrics: authentication & identification (definition, trends, use cases, laws and latest news)](https://www.thalesgroup.com/en/markets/digital-identity-and-security/government/inspired/biometrics)
      * [Biometric Devices: Cost, Types and Comparative Analysis](https://www.bayometric.com/biometric-devices-cost/)
  * [Deniable authentication](https://en.wikipedia.org/wiki/Deniable\_authentication)

* __Application of Cryptography__
  * [Web of trust](https://en.wikipedia.org/wiki/Web\_of\_trust)
  * [Pretty Good Privacy](https://en.wikipedia.org/wiki/Pretty\_Good\_Privacy)
    * [GNU Privacy Guard](https://en.wikipedia.org/wiki/GNU\_Privacy\_Guard)
      * [GnuPG](https://gnupg.org/)
      * [Gnu Privacy Guard (GnuPG) Mini Howto](https://www.dewinter.com/gnupg_howto/english/GPGMiniHowto.html)
      * [How to display gpg key details without importing it?](https://stackoverflow.com/questions/22136029/how-to-display-gpg-key-details-without-importing-it)
  * [Steganography](https://en.wikipedia.org/wiki/Steganography)
    * [OpenStego](https://www.openstego.com/)
    * [SteGUI](http://stegui.sourceforge.net/)
    * [Stegosuite](https://stegosuite.org/)
  * [Secure Shell](https://en.wikipedia.org/wiki/Secure\_Shell)
    * [How to Set Up SSH Keys on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804)
    * [Connecting to GitHub with SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
    * [Ubuntu Server Guide](https://ubuntu.com/server/docs)
  * _Secure email_
    * [Email privacy](https://en.wikipedia.org/wiki/Email\_privacy)
    * [Mailvelope](https://www.mailvelope.com)
  * _File system encryption_
    * [Encrypting File System](https://en.wikipedia.org/wiki/Encrypting\_File\_System)
    * [Disk encryption software](https://en.wikipedia.org/wiki/Disk\_encryption\_software)
      * [VeraCrypt](https://www.veracrypt.fr/en/Home.html)
      * [BitLocker](https://en.wikipedia.org/wiki/BitLocker)
  * _Securing cloud_
    * [Cloud Security Alliance](https://en.wikipedia.org/wiki/Cloud\_Security\_Alliance)
      * [CSA](https://cloudsecurityalliance.org/)
    * [MEGA](https://mega.nz/)
      * [MEGA source code](https://github.com/meganz)


## online tools

* [HMAC Generator](https://codebeautify.org/hmac-generator)