# Verosent's Certificate Authority
The Verosent Certificate Authority is only being used for a small amount of services hosted by [Verosent](https://www.verosent.com).

As of now, the Certificate Authority issues certificates for...

* Verosent's MariaDB database servers for external connections by our customers
* Verosent's FTP servers that serve our customer's Game Server files

We do not issue certificates to third-parties and we do not plan to become an official supported Certificate Authority trusted by browsers.

Certificate Fingerprint (SHA256): `21:6C:49:3B:83:A7:1C:14:CC:EE:16:7F:55:FC:6A:C0:DE:98:76:E0:1B:98:FA:B0:6A:19:4C:22:E6:73:C7:A7`

The certificate chain file can be found in the [chain.pem](https://raw.githubusercontent.com/verosent/certificate-authority/main/chain.pem) of this repository.
