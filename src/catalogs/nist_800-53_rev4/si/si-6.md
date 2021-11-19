# si-6 - \[System and Information Integrity\] Security Function Verification

## Control Statement

The information system:

- \[a\] Verifies the correct operation of {{ insert: param, si-6_prm_1 }};

- \[b\] Performs this verification {{ insert: param, si-6_prm_2 }};

- \[c\] Notifies {{ insert: param, si-6_prm_5 }} of failed security verification tests; and

- \[d\]  {{ insert: param, si-6_prm_6 }} when anomalies are discovered.

## Control Objective

Determine if:

- \[a_obj\]

  - \[1\] the organization defines security functions to be verified for correct operation;
  - \[2\] the information system verifies the correct operation of organization-defined security functions;

- \[b_obj\]

  - \[1\] the organization defines system transitional states requiring verification of organization-defined security functions;
  - \[2\] the organization defines a frequency to verify the correct operation of organization-defined security functions;
  - \[3\] the information system performs this verification one or more of the following:

    - \[a\] at organization-defined system transitional states;
    - \[b\] upon command by user with appropriate privilege; and/or
    - \[c\] with the organization-defined frequency;

- \[c_obj\]

  - \[1\] the organization defines personnel or roles to be notified of failed security verification tests;
  - \[2\] the information system notifies organization-defined personnel or roles of failed security verification tests;

- \[d_obj\]

  - \[1\] the organization defines alternative action(s) to be performed when anomalies are discovered;
  - \[2\] the information system performs one or more of the following actions when anomalies are discovered:

    - \[a\] shuts the information system down;
    - \[b\] restarts the information system; and/or
    - \[c\] performs organization-defined alternative action(s).

## Control guidance

Transitional states for information systems include, for example, system startup, restart, shutdown, and abort. Notifications provided by information systems include, for example, electronic alerts to system administrators, messages to local computer consoles, and/or hardware indications such as lights.
