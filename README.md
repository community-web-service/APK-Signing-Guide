# APK-Signing-Guide
Detailed information on keystore generation, APK alignment, and APK signing.

[Read the guide here.](apk-signing-guide.md)

## To-Do
* Explain how a public key is stored within a certificate.
* Explain how APK signature validation works.
* Add instructions for how to install and configure both JDK and Android SDK Build Tools
* Consider adding a tl;dr section
* Determine if Android API Level >= 24 with APK Signature Scheme v2 supports MD5, SHA1, and SHA384.
* Explain why it is important to use secure hash functions and key algorithms when signing APKs
	* Future proofing against depreciation.
	* Prevention of collision attacks.
* Explain different hash functions and key algorithms.
* Note that apksigner can accept a keyfile and a certificate file in place of a keystore.
* List additional apksigner commands.
* Explain how to generate a debug keystore.
* Consider adding examples.
* Detail z flag for zipalign.
