# LSA Public Runtime

Public, sanitized execution surface for Lyra Sha Agency (LSA).

## Boundary

This repository is an **execution surface only**. It is not an institutional authority source.

Do not place in this repository:
- private LSA governance or institutional records;
- private commissions or customer/client data;
- credentials, tokens, secrets, or private endpoints;
- protected Council materials or private evidence.

Authoritative LSA governance remains in LSA-controlled private infrastructure.

## Evidence rule

Runtime artifacts and receipts must record the actual event time using canonical UTC ISO 8601 timestamps and identify provenance. Render time must not masquerade as event time. Synthetic/test data must be clearly identified as synthetic/test data.

## Bridge architecture

The public runtime never receives standing access to the private LSA repository. A private-side exporter may release only a deliberately sanitized job packet. Public output is returned as **UNVERIFIED EXECUTION OUTPUT** and does not become institutional truth, Vera verification, Diana approval, or Founder approval merely because a workflow succeeded.

Bridge proof requires a matching commission ID across the private-side source receipt, sanitized public job packet, public execution receipt, returned evidence package, and private verification intake.

Until all five are evidenced, the bridge is **NOT PROVEN**.

## Current status

Public hosted compute proof: **PROVEN** by Run 35815959458 on 2026-09-23T03:51:07Z.

Private-to-public-to-private bridge: **NOT YET PROVEN**.

No private-LSA repository access is authorized from this public repository.
