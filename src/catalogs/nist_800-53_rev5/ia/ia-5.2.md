# ia-5.2 - \[Identification and Authentication\] Implement a local cache of revocation data to support path discovery and validation.

## Control Statement

Discussion: Public key cryptography is a valid authentication mechanism for individuals and machines or devices. When PKI is implemented, status information for certification paths includes certificate revocation lists or certificate status protocol responses. For PIV cards, certificate validation involves the construction and verification of a certification path to the Common Policy Root trust anchor which includes certificate policy processing. Implementing a local cache of revocation data to support path discovery and validation supports system availability in situations where organizations are unable to access revocation information via the network.
