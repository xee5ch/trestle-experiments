# ia-9.2 - \[Identification and Authentication\] Transmission of Decisions

## Control Statement

The organization ensures that identification and authentication decisions are transmitted between {{ insert: param, ia-9.2_prm_1 }} consistent with organizational policies.

## Control Objective

Determine if the organization:

- \[1\] defines services for which identification and authentication decisions transmitted between such services are to be consistent with organizational policies; and

- \[2\] ensures that identification and authentication decisions are transmitted between organization-defined services consistent with organizational policies.

## Control guidance

For distributed architectures (e.g., service-oriented architectures), the decisions regarding the validation of identification and authentication claims may be made by services separate from the services acting on those decisions. In such situations, it is necessary to provide the identification and authentication decisions (as opposed to the actual identifiers and authenticators) to the services that need to act on those decisions.
