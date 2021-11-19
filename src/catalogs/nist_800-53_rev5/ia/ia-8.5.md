# ia-8.5 - \[Identification and Authentication\] Acceptance of PIV-I Credentials

## Control Statement

Accept and verify federated or PKI credentials that meet {{ insert: param, ia-8.5_prm_1 }}.

## Control guidance

This control enhancement can be implemented by PIV , PIV-I, and other commercial or external identity providers. Acceptance and verification of Personal Identity Verification (PIV)-I-compliant credentials applies to both logical and physical access control systems. Acceptance and verification of PIV-I credentials addresses nonfederal issuers of identity cards that desire to interoperate with United States Government PIV systems and that can be trusted by federal government-relying parties. The X.509 certificate policy for the Federal Bridge Certification Authority (FBCA) addresses PIV-I requirements. The PIV-I card is commensurate with the PIV credentials as defined in cited references. PIV-I credentials are the credentials issued by a PIV-I provider whose PIV-I certificate policy maps to the Federal Bridge PIV-I Certificate Policy. A PIV-I provider is cross-certified with the FBCA (directly or through another PKI bridge) with policies that have been mapped and approved as meeting the requirements of the PIV-I policies defined in the FBCA certificate policy.
