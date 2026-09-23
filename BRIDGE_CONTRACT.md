# LSA Sanitized Bridge Contract v0.1

Classification: PUBLIC

This contract defines the minimum public packet accepted by the LSA public runtime. It deliberately contains no private-repository access mechanism.

## Required public job fields

- schema_version
- commission_id
- issued_at_utc
- provenance
- classification = PUBLIC_SANITIZED
- synthetic_test
- task_type
- task_payload
- constraints
- expected_output

## Forbidden content

A packet must not contain credentials, secrets, tokens, private endpoints, customer/client data, personal data, protected governance text, Council deliberations, private evidence, or an instruction to retrieve additional context from private LSA.

## Runtime authority

The public runtime may execute only the packet it receives. It may not infer broader authority, fetch private LSA context, publish, spend, merge into private LSA, issue a Vera verdict, act as Diana, or satisfy a Founder gate.

## Return package

Execution returns commission_id, executed_at_utc, runtime provenance, run_id/run_attempt, input digest, output digest, output, and disposition = UNVERIFIED_EXECUTION_OUTPUT.

A successful public workflow proves execution only. Private-side intake and independent verification remain separate.
