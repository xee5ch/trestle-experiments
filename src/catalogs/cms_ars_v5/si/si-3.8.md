# si-3.8 - \[System and Information Integrity\] Detect Unauthorized Commands

## Control Statement

- \[a\] Detect the following unauthorized operating system commands through the kernel application programming interface on {{ insert: param, si-3.8_prm_1 }}: {{ insert: param, si-3.8_prm_2 }}; and

- \[b\]  {{ insert: param, si-3.8_prm_3 }}.

## Control guidance

Detecting unauthorized commands can be applied to critical interfaces other than kernel-based interfaces, including interfaces with virtual machines and privileged applications. Unauthorized operating system commands include commands for kernel functions from system processes that are not trusted to initiate such commands, or commands for kernel functions that are suspicious even though commands of that type are reasonable for processes to initiate. Organizations can define the malicious commands to be detected by a combination of command types, command classes, or specific instances of commands. Organizations can also define hardware components by component type, component, component location in the network, or combination therein. Organizations may select different actions for different types, classes, or instances of malicious commands.
