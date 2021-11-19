# ac-3.3 - \[Access Control\] Mandatory Access Control

## Control Statement

The information system enforces {{ insert: param, ac-3.3_prm_1 }} over all subjects and objects where the policy:

- \[a\] Is uniformly enforced across all subjects and objects within the boundary of the information system;

- \[b\] Specifies that a subject that has been granted access to information is constrained from doing any of the following;

  - \[1\] Passing the information to unauthorized subjects or objects;
  - \[2\] Granting its privileges to other subjects;
  - \[3\] Changing one or more security attributes on subjects, objects, the information system, or information system components;
  - \[4\] Choosing the security attributes and attribute values to be associated with newly created or modified objects; or
  - \[5\] Changing the rules governing access control; and

- \[c\] Specifies that {{ insert: param, ac-3.3_prm_2 }} may explicitly be granted {{ insert: param, ac-3.3_prm_3 }} such that they are not limited by some or all of the above constraints.

## Control Objective

Determine if:

- \[1\] the organization defines mandatory access control policies to be enforced over all subjects and objects;

- \[2\] the organization defines subjects over which organization-defined mandatory access control policies are to be enforced;

- \[3\] the organization defines objects over which organization-defined mandatory access control policies are to be enforced;

- \[4\] the organization defines subjects that may explicitly be granted privileges such that they are not limited by the constraints specified elsewhere within this control;

- \[5\] the organization defines privileges that may be granted to organization-defined subjects;

- \[6\] the information system enforces organization-defined mandatory access control policies over all subjects and objects where the policy specifies that:

  - \[6\] the policy is uniformly enforced across all subjects and objects within the boundary of the information system;
  - \[6\] a subject that has been granted access to information is constrained from doing any of the following:

    - \[6\] passing the information to unauthorized subjects or objects;
    - \[6\] granting its privileges to other subjects;
    - \[6\] changing one or more security attributes on:

      - \[a\] subjects;
      - \[b\] objects;
      - \[c\] the information system; or
      - \[d\] system components;

    - \[6\] choosing the security attributes and attribute values to be associated with newly created or modified objects; or
    - \[6\] changing the rules governing access control; and

  - \[6\] organization-defined subjects may explicitly be granted organization-defined privileges such that they are not limited by some or all of the above constraints.

## Control guidance

Mandatory access control as defined in this control enhancement is synonymous with nondiscretionary access control, and is not constrained only to certain historical uses (e.g., implementations using the Bell-LaPadula Model). The above class of mandatory access control policies constrains what actions subjects can take with information obtained from data objects for which they have already been granted access, thus preventing the subjects from passing the information to unauthorized subjects and objects. This class of mandatory access control policies also constrains what actions subjects can take with respect to the propagation of access control privileges; that is, a subject with a privilege cannot pass that privilege to other subjects. The policy is uniformly enforced over all subjects and objects to which the information system has control. Otherwise, the access control policy can be circumvented. This enforcement typically is provided via an implementation that meets the reference monitor concept (see AC-25). The policy is bounded by the information system boundary (i.e., once the information is passed outside of the control of the system, additional means may be required to ensure that the constraints on the information remain in effect). The trusted subjects described above are granted privileges consistent with the concept of least privilege (see AC-6). Trusted subjects are only given the minimum privileges relative to the above policy necessary for satisfying organizational mission/business needs. The control is most applicable when there is some policy mandate (e.g., law, Executive Order, directive, or regulation) that establishes a policy regarding access to sensitive/classified information and some users of the information system are not authorized access to all sensitive/classified information resident in the information system. This control can operate in conjunction with AC-3 (4). A subject that is constrained in its operation by policies governed by this control is still able to operate under the less rigorous constraints of AC-3 (4), but policies governed by this control take precedence over the less rigorous constraints of AC-3 (4). For example, while a mandatory access control policy imposes a constraint preventing a subject from passing information to another subject operating at a different sensitivity label, AC-3 (4) permits the subject to pass the information to any subject with the same sensitivity label as the subject.
