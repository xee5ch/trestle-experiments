# sa-8.2 - \[System and Services Acquisition\] Least Common Mechanism

## Control Statement

Implement the security design principle of least common mechanism in {{ insert: param, sa-8.2_prm_1 }}.

## Control guidance

The principle of least common mechanism states that the amount of mechanism common to more than one user and depended on by all users is minimized [POPEK74]. Minimization of mechanism implies that different components of a system refrain from using the same mechanism to access a system resource. Every shared mechanism (especially a mechanism involving shared variables) represents a potential information path between users and is designed with great care to be sure it does not unintentionally compromise security [SALTZER75]. Implementing the principle of least common mechanism helps to reduce the adverse consequences of sharing system state among different programs. A single program corrupting a shared state (including shared variables) has the potential to corrupt other programs that are dependent on the state. The principle of least common mechanism also supports the principle of simplicity of design and addresses the issue of covert storage channels [LAMPSON73].
