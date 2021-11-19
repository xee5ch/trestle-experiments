# cm-8.5 - \[Configuration Management\] No Duplicate Accounting of Components

## Control Statement

- \[a\] Verify that all components within the system are not duplicated in other system component inventories; or

- \[b\] If a centralized component inventory is used, verify components are not assigned to multiple systems.

## Control guidance

Preventing duplicate accounting of system components addresses the lack of accountability that occurs when component ownership and system association is not known, especially in large or complex connected systems. For software inventory, centrally managed software that is accessed via other systems is addressed as a component of the system on which it is installed and managed. Software installed on multiple organizational systems and managed at the system level is addressed for each individual system and may appear more than once in a centralized component inventory, necessitating a system association for each software instance in the centralized inventory to avoid duplicate accounting of components. Scanning systems implementing multiple network protocols (e.g., IPv4 and IPv6) can result in duplicate components being identified in different address spaces. The implementation of CM-8(7) can help to eliminate duplicate accounting of components.
