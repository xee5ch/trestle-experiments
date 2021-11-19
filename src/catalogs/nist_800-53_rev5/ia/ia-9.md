# ia-9 - \[Identification and Authentication\] Service Identification and Authentication

## Control Statement

Uniquely identify and authenticate {{ insert: param, ia-9_prm_1 }} before establishing communications with devices, users, or other services or applications.

## Control guidance

Services that may require identification and authentication include web applications using digital certificates or services or applications that query a database. Identification and authentication methods for system services/applications include information or code signing, provenance graphs, and/or electronic signatures indicating the sources of services. Decisions regarding the validation of identification and authentication claims can be made by services separate from the services acting on those decisions. This can occur in distributed system architectures. In such situations, the identification and authentication decisions (instead of actual identifiers and authenticators) are provided to the services that need to act on those decisions.
