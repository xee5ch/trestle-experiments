# ia-4 - \[Identification and Authentication\] Identifier Management

## Control Statement

The organization manages information system identifiers by:

- \[a\] Receiving authorization from {{ insert: param, ia-4_prm_1 }} to assign an individual, group, role, or device identifier;

- \[b\] Selecting an identifier that identifies an individual, group, role, or device;

- \[c\] Assigning the identifier to the intended individual, group, role, or device;

- \[d\] Preventing reuse of identifiers for {{ insert: param, ia-4_prm_2 }}; and

- \[e\] Disabling the identifier after {{ insert: param, ia-4_prm_3 }}.

## Control Objective

Determine if the organization manages information system identifiers by:

- \[a_obj\]

  - \[1\] defining personnel or roles from whom authorization must be received to assign:

    - \[a\] an individual identifier;
    - \[b\] a group identifier;
    - \[c\] a role identifier; and/or
    - \[d\] a device identifier;

  - \[2\] receiving authorization from organization-defined personnel or roles to assign:

    - \[a\] an individual identifier;
    - \[b\] a group identifier;
    - \[c\] a role identifier; and/or
    - \[d\] a device identifier;

- \[b_obj\] selecting an identifier that identifies:

  - \[1\] an individual;
  - \[2\] a group;
  - \[3\] a role; and/or
  - \[4\] a device;

- \[c_obj\] assigning the identifier to the intended:

  - \[1\] individual;
  - \[2\] group;
  - \[3\] role; and/or
  - \[4\] device;

- \[d_obj\]

  - \[1\] defining a time period for preventing reuse of identifiers;
  - \[2\] preventing reuse of identifiers for the organization-defined time period;

- \[e_obj\]

  - \[1\] defining a time period of inactivity to disable the identifier; and
  - \[2\] disabling the identifier after the organization-defined time period of inactivity.

## Control guidance

Common device identifiers include, for example, media access control (MAC), Internet protocol (IP) addresses, or device-unique token identifiers. Management of individual identifiers is not applicable to shared information system accounts (e.g., guest and anonymous accounts). Typically, individual identifiers are the user names of the information system accounts assigned to those individuals. In such instances, the account management activities of AC-2 use account names provided by IA-4. This control also addresses individual identifiers not necessarily associated with information system accounts (e.g., identifiers used in physical security control databases accessed by badge reader systems for access to information systems). Preventing reuse of identifiers implies preventing the assignment of previously used individual, group, role, or device identifiers to different individuals, groups, roles, or devices.
