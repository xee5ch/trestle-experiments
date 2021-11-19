# ia-2.6 - \[Identification and Authentication\] Access to Accounts — Separate Device

## Control Statement

Implement multifactor authentication for {{ insert: param, ia-2.6_prm_1 }} access to {{ insert: param, ia-2.6_prm_2 }} such that:

- \[a\] One of the factors is provided by a device separate from the system gaining access; and

- \[b\] The device meets {{ insert: param, ia-2.6_prm_3 }}.

## Control guidance

The purpose of requiring a device that is separate from the system to which the user is attempting to gain access for one of the factors during multifactor authentication is to reduce the likelihood of compromising authentication credentials stored on the system. Adversaries may be able to compromise credentials stored on the system and subsequently impersonate authorized users. Implementing one of the factors in multifactor authentication (e.g., a hardware token) on a separate device, provides a greater strength of mechanism and an increased level of assurance in the authentication process.
