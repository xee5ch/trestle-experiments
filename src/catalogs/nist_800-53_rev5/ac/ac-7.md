# ac-7 - \[Access Control\] Unsuccessful Logon Attempts

## Control Statement

- \[a\] Enforce a limit of {{ insert: param, ac-7_prm_1 }} consecutive invalid logon attempts by a user during a {{ insert: param, ac-7_prm_2 }}; and

- \[b\] Automatically {{ insert: param, ac-7_prm_3 }} when the maximum number of unsuccessful attempts is exceeded.

## Control guidance

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by systems are usually temporary and automatically release after a predetermined, organization-defined time period. If a delay algorithm is selected, organizations may employ different algorithms for different components of the system based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at the operating system and the application levels. Organization-defined actions that may be taken when the number of allowed consecutive invalid logon attempts is exceeded include prompting the user to answer a secret question in addition to the username and password; invoking a lockdown mode with limited user capabilities (instead of full lockout); or comparing the IP address to a list of known IP addresses for the user and then allowing additional logon attempts if the attempts are from a known IP address. Techniques to help prevent brute force attacks in lieu of an automatic system lockout or the execution of delay algorithms support the objective of availability while still protecting against such attacks. Techniques that are effective when used in combination include prompting the user to respond to a secret question before the number of allowed unsuccessful logon attempts is exceeded; allowing users to logon only from specified IP addresses; requiring a CAPTCHA to prevent automated attacks; or applying user profiles such as location, time of day, IP address, device, or MAC address. Automatically unlocking an account after a specified period of time is generally not permitted. However, exceptions may be required based on operational mission or need.
