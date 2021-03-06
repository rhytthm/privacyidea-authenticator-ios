# privacyIDEA

The privacyIDEA is a modular authentication server that can be used to enhance the security of your existing applications like local login, VPN, remote access, SSH connections, access to web sites or web portals with two factor authentication. Originally it was used for OTP (One Time Password) authentication devices – being an OTP server. But other “devices” like challenge response, U2F, Yubikeys, SSH keys and x509 certificates are also available. It runs on Linux and is completely Open Source, licensed under the AGPLv3.


# privacyIDEA Authenticator for iOS

The privacyIDEA Authenticator currently implements the HOTP and TOTP (30 and 60 seconds) algorithms with SHA-1/SHA-256/SHA-512.
It can scan QR codes according to the
[Google Authenticator Key URI](https://github.com/google/google-authenticator/wiki/Key-Uri-Format).

The privacyIDEA Authenticator also provides a more secure way of enrollment as
specified in our
[smartphone concept](https://github.com/privacyidea/privacyidea/wiki/concept%3A-SmartphoneApp) as well as the [pushtoken](https://github.com/privacyidea/privacyidea/wiki/concept%3A-PushToken) with support for user-configured firebase projects.

The App is best used with the
[privacyIDEA Authentication Server](https://github/privacyidea/privacyidea).

The Android App can be found [here](https://github.com/privacyidea/privacyidea-authenticator).

# Todos

See the issues.

Ideas and pull requests are welcome.
