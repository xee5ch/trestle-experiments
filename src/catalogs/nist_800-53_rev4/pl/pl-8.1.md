# pl-8.1 - \[Planning\] Defense-in-depth

## Control Statement

The organization designs its security architecture using a defense-in-depth approach that:

- \[a\] Allocates {{ insert: param, pl-8.1_prm_1 }} to {{ insert: param, pl-8.1_prm_2 }}; and

- \[b\] Ensures that the allocated security safeguards operate in a coordinated and mutually reinforcing manner.

## Control Objective

Determine if the organization:

- \[a_obj\]

  - \[1\] defines security safeguards to be allocated to locations and architectural layers within the design of its security architecture;
  - \[2\] defines locations and architectural layers of its security architecture in which organization-defined security safeguards are to be allocated;
  - \[3\] designs its security architecture using a defense-in-depth approach that allocates organization-defined security safeguards to organization-defined locations and architectural layers; and

- \[b_obj\] designs its security architecture using a defense-in-depth approach that ensures the allocated organization-defined security safeguards operate in a coordinated and mutually reinforcing manner.

## Control guidance

Organizations strategically allocate security safeguards (procedural, technical, or both) in the security architecture so that adversaries have to overcome multiple safeguards to achieve their objective. Requiring adversaries to defeat multiple mechanisms makes it more difficult to successfully attack critical information resources (i.e., increases adversary work factor) and also increases the likelihood of detection. The coordination of allocated safeguards is essential to ensure that an attack that involves one safeguard does not create adverse unintended consequences (e.g., lockout, cascading alarms) by interfering with another safeguard. Placement of security safeguards is a key activity. Greater asset criticality or information value merits additional layering. Thus, an organization may choose to place anti-virus software at organizational boundary layers, email/web servers, notebook computers, and workstations to maximize the number of related safeguards adversaries must penetrate before compromising the information and information systems.
