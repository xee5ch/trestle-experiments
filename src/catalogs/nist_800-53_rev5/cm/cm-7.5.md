# cm-7.5 - \[Configuration Management\] Authorized Software — Whitelisting

## Control Statement

- \[a\] Identify {{ insert: param, cm-7.5_prm_1 }};

- \[b\] Employ a deny-all, permit-by-exception policy to allow the execution of authorized software programs on the system; and

- \[c\] Review and update the list of authorized software programs {{ insert: param, cm-7.5_prm_2 }}.

## Control guidance

The process used to identify specific software programs or entire categories of software programs that are authorized to execute on organizational systems is commonly referred to as whitelisting. Software programs identified can be limited to specific versions or from a specific source. To facilitate comprehensive whitelisting and increase the strength of protection for attacks that bypass application level whitelisting, software programs may be decomposed into and monitored at different levels of detail. Software program levels of detail include applications, application programming interfaces, application modules, scripts, system processes, system services, kernel functions, registries, drivers, and dynamic link libraries. The concept of whitelisting may also be applied to user actions, ports, IP addresses, and media access control (MAC) addresses. Organizations consider verifying the integrity of white-listed software programs using, cryptographic checksums, digital signatures, or hash functions. Verification of white-listed software can occur either prior to execution or at system startup. Whitelisting of URLs for websites is addressed in CA-3(5) and SC-7.
