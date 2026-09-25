# Authentication Decision

Decision for Phase 1: GitHub App + Device Flow.

Reason: Ebon runs in a headless/ephemeral environment. Device Flow lets Nera authorize a session without emailing or persisting a long-lived PAT. The app installation can be limited to this repository and Issues read/write permission.

This decision can be revisited after the manual forum workflow is proven.
