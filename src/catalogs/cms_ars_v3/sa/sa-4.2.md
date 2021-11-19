# sa-4.2 - \[System and Services Acquisition\] Design / Implementation Information for Security Controls

## Control Statement

The organization requires the developer of the information system, system component, or information system service to provide design and implementation information for the security controls to be employed that includes: {{ insert: param, sa-4.2_prm_1 }} at {{ insert: param, sa-4.2_prm_3 }}.

## Control Objective

Determine if the organization:

- \[1\] defines level of detail that the developer is required to provide in design and implementation information for the security controls to be employed in the information system, system component, or information system service;

- \[2\] defines design/implementation information that the developer is to provide for the security controls to be employed (if selected);

- \[3\] requires the developer of the information system, system component, or information system service to provide design and implementation information for the security controls to be employed that includes, at the organization-defined level of detail, one or more of the following:

  - \[a\] security-relevant external system interfaces;
  - \[b\] high-level design;
  - \[c\] low-level design;
  - \[d\] source code;
  - \[e\] hardware schematics; and/or
  - \[f\] organization-defined design/implementation information.

## Control guidance

Organizations may require different levels of detail in design and implementation documentation for security controls employed in organizational information systems, system components, or information system services based on mission/business requirements, requirements for trustworthiness/resiliency, and requirements for analysis and testing. Information systems can be partitioned into multiple subsystems. Each subsystem within the system can contain one or more modules. The high-level design for the system is expressed in terms of multiple subsystems and the interfaces between subsystems providing security-relevant functionality. The low-level design for the system is expressed in terms of modules with particular emphasis on software and firmware (but not excluding hardware) and the interfaces between modules providing security-relevant functionality. Source code and hardware schematics are typically referred to as the implementation representation of the information system.
