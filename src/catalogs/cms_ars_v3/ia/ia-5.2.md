# ia-5.2 - \[Identification and Authentication\] Pki-based Authentication

## Control Statement

The information system, for PKI-based authentication:

- \[a\] Validates certifications by constructing and verifying a certification path to an accepted trust anchor including checking certificate status information;

- \[b\] Enforces authorized access to the corresponding private key;

- \[c\] Maps the authenticated identity to the account of the individual or group; and

- \[d\] Implements a local cache of revocation data to support path discovery and validation in case of inability to access revocation information via the network.

## Control Objective

Determine if the information system, for PKI-based authentication:

- \[a_obj\]

  - \[1\] validates certifications by constructing a certification path to an accepted trust anchor;
  - \[2\] validates certifications by verifying a certification path to an accepted trust anchor;
  - \[3\] includes checking certificate status information when constructing and verifying the certification path;

- \[b_obj\] enforces authorized access to the corresponding private key;

- \[c_obj\] maps the authenticated identity to the account of the individual or group; and

- \[d_obj\] implements a local cache of revocation data to support path discovery and validation in case of inability to access revocation information via the network.

## Control guidance

Status information for certification paths includes, for example, certificate revocation lists or certificate status protocol responses. For PIV cards, validation of certifications involves the construction and verification of a certification path to the Common Policy Root trust anchor including certificate policy processing.
