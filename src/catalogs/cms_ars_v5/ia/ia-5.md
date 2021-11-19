# ia-5 - \[Identification and Authentication\] Authenticator Management

## Control Statement

Manage system authenticators by:

- \[a\] Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, service, or device receiving the authenticator;

- \[b\] Establishing initial authenticator content for any authenticators issued by the organization;

- \[c\] Ensuring that authenticators have sufficient strength of mechanism for their intended use;

- \[d\] Establishing and implementing administrative procedures for initial authenticator distribution, for lost or compromised or damaged authenticators, and for revoking authenticators;

- \[e\] Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators;

- \[f\] Changing default authenticators prior to first use;

- \[g\] Changing or refreshing authenticators {{ insert: param, ia-5_prm_1 }};

- \[h\] Protecting authenticator content from unauthorized disclosure and modification;

- \[i\] Requiring individuals to take, and having devices implement, specific controls to protect authenticators; and

- \[j\] Changing authenticators for group or role accounts when membership to those accounts changes.

## Control guidance

Authenticators include passwords, cryptographic devices, one-time password devices, and key cards. Device authenticators include certificates and passwords. Initial authenticator content is the actual content of the authenticator (e.g., the initial password). In contrast, the requirements about authenticator content contain specific characteristics or criteria (e.g., minimum password length). Developers may deliver system components with factory default authentication credentials to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant security risk. The requirement to protect individual authenticators may be implemented via control PL-4 or PS-6 for authenticators in the possession of individuals and by controls AC-3, AC-6, and SC-28 for authenticators stored in organizational systems, including passwords stored in hashed or encrypted formats or files containing encrypted or hashed passwords accessible with administrator privileges. Systems support authenticator management by organization-defined settings and restrictions for various authenticator characteristics (e.g., minimum password length, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication). Actions can be taken to safeguard individual authenticators, including maintaining possession of authenticators; not sharing authenticators with others; and reporting lost, stolen, or compromised authenticators immediately. Authenticator management includes issuing and revoking authenticators for temporary access when no longer needed.
