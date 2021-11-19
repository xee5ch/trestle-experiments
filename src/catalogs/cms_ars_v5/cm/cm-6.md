# cm-6 - \[Configuration Management\] Configuration Settings

## Control Statement

- \[a\] Establish and document configuration settings for components employed within the system using {{ insert: param, cm-6_prm_1 }} that reflect the most restrictive mode consistent with operational requirements;

- \[b\] Implement the configuration settings;

- \[c\] Identify, document, and approve any deviations from established configuration settings for {{ insert: param, cm-6_prm_2 }} based on {{ insert: param, cm-6_prm_3 }}; and

- \[d\] Monitor and control changes to the configuration settings in accordance with organizational policies and procedures.

## Control guidance

Configuration settings are the parameters that can be changed in the hardware, software, or firmware components of the system that affect the security posture or functionality of the system. Information technology products for which security-related configuration settings can be defined include mainframe computers, servers, workstations, operating systems, mobile devices, input/output devices, protocols, and applications. Security parameters are parameters impacting the security posture of systems, including the parameters required to satisfy other security control requirements. Security parameters include registry settings; account, file, or directory permission settings; and settings for functions, protocols, ports, services, and remote connections. Organizations establish organization-wide configuration settings and subsequently derive specific configuration settings for systems. The established settings become part of the configuration baseline for the system. Common secure configurations (also known as security configuration checklists, lockdown and hardening guides, security reference guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for information technology products and platforms as well as instructions for configuring those products or platforms to meet operational requirements. Common secure configurations can be developed by a variety of organizations, including information technology product developers, manufacturers, vendors, federal agencies, consortia, academia, industry, and other organizations in the public and private sectors. Implementation of a common secure configuration may be mandated at the organization level, mission/business process level, or system level, or may be mandated at a higher level, including by a regulatory agency. Common secure configurations include the United States Government Configuration Baseline [USGCB] and security technical implementation guides (STIGs), which affect the implementation of CM-6 and other controls such as AC-19 and CM-7. The Security Content Automation Protocol (SCAP) and the defined standards within the protocol provide an effective method to uniquely identify, track, and control configuration settings.
