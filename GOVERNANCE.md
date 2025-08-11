# Governance (v0.1)
Roles: Public Lead, Anonymous Steward (release/kill keys), Maintainers Council, Safety Team, Reviewers, Contributors.

Flow: PR → CI green → 2 maintainer approvals → community vote (quorum 25, ≥66%) → Council co‑sign → Steward signs release.

Emergency (permission to kill): triggers = malware/exploit, safety-bypass, data-exfil, privilege‑esc. Action = revoke keys/CRL, feature-flag disable, hotfix. Expires in 7 days unless Council ratifies. Public incident note in 72h.
