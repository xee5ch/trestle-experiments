# sc-7.11 - \[System and Communications Protection\] Restrict Incoming Communications Traffic

## Control Statement

The information system only allows incoming communications from {{ insert: param, sc-7.11_prm_1 }} to be routed to {{ insert: param, sc-7.11_prm_2 }}.

## Control Objective

Determine if:

- \[1\] the organization defines internal communications traffic to be routed to external networks;

- \[2\] the organization defines authorized destinations only to which that incoming communications from organization-defined authorized sources may be routed; and

- \[3\] the information system only allows incoming communications from organization-defined authorized sources to be routed to organization-defined authorized destinations.

## Control guidance

This control enhancement provides determinations that source and destination address pairs represent authorized/allowed communications. Such determinations can be based on several factors including, for example, the presence of source/destination address pairs in lists of authorized/allowed communications, the absence of address pairs in lists of unauthorized/disallowed pairs, or meeting more general rules for authorized/allowed source/destination pairs.
