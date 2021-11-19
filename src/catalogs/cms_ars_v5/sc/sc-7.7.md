# sc-7.7 - \[System and Communications Protection\] Prevent Split Tunneling for Remote Devices

## Control Statement

Prevent a remote device from simultaneously establishing non-remote connections with the system and communicating via some other connection to resources in external networks.

## Control guidance

Prevention of split tunneling is implemented in remote devices through configuration settings to disable split tunneling in those devices, and by preventing those configuration settings from being configurable by users. Prevention of split tunneling is implemented within the system by the detection of split tunneling (or of configuration settings that allow split tunneling) in the remote device, and by prohibiting the connection if the remote device is using split tunneling. Split tunneling might be desirable by remote users to communicate with local system resources such as printers or file servers. However, split tunneling can facilitate unauthorized external connections, making the system vulnerable to attack and to exfiltration of organizational information.
