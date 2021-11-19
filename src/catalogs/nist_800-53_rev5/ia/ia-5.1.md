# ia-5.1 - \[Identification and Authentication\] Password-based Authentication

## Control Statement

For password-based authentication:

- \[a\] Maintain a list of commonly-used, expected, or compromised passwords and update the list {{ insert: param, ia-5.1_prm_1 }} and when organizational passwords are suspected to have been compromised directly or indirectly;

- \[b\] Verify, when users create or update passwords, that the passwords are not found on the organization-defined list of commonly-used, expected, or compromised passwords;

- \[c\] Transmit only cryptographically-protected passwords;

- \[d\] Store passwords using an approved hash algorithm and salt, preferably using a keyed hash;

- \[e\] Require immediate selection of a new password upon account recovery;

- \[f\] Allow user selection of long passwords and passphrases, including spaces and all printable characters;

- \[g\] Employ automated tools to assist the user in selecting strong password authenticators; and

- \[h\] Enforce the following composition and complexity rules: {{ insert: param, ia-5.1_prm_2 }}.

## Control guidance

Password-based authentication applies to passwords regardless of whether they are used in single-factor or multifactor authentication. Long passwords or passphrases are preferable over shorter passwords. Enforced composition rules provide marginal security benefit while decreasing usability. However, organizations may choose to establish certain rules for password generation (e.g., minimum character length for long passwords) under certain circumstances and can enforce this requirement in IA-5(1)(h). Account recovery can occur, for example, in situations when a password is forgotten. Cryptographically-protected passwords include salted one-way cryptographic hashes of passwords. The list of commonly-used, compromised, or expected passwords includes passwords obtained from previous breach corpuses, dictionary words, and repetitive or sequential characters. The list includes context specific words, for example, the name of the service, username, and derivatives thereof.
