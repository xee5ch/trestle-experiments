# sc-7.10 - \[System and Communications Protection\] Prevent Exfiltration

## Control Statement

- \[a\] Prevent the exfiltration of information; and

- \[b\] Conduct exfiltration tests {{ insert: param, sc-7.10_prm_1 }}.

## Control guidance

This control applies to intentional and unintentional exfiltration of information. Controls to prevent exfiltration of information from systems may be implemented at internal endpoints, external boundaries, and across managed interfaces and include adherence to protocol formats; monitoring for beaconing activity from systems; disconnecting external network interfaces except when explicitly needed; employing traffic profile analysis to detect deviations from the volume and types of traffic expected or call backs to command and control centers; monitoring for steganography; disassembling and reassembling packet headers; and employing data loss and data leakage prevention tools. Devices that enforce strict adherence to protocol formats include deep packet inspection firewalls and XML gateways. The devices verify adherence to protocol formats and specifications at the application layer and identify vulnerabilities that cannot be detected by devices operating at the network or transport layers. Prevention of exfiltration is similar to data loss prevention or data leakage prevention and is closely associated with cross-domain solutions and system guards enforcing information flow requirements.
