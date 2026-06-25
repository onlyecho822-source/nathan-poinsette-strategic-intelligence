# ECHO UNIVERSE — SECURITY RISK REGISTER

**Generated:** 2026-06-24  
**Status:** READ-ONLY — For tracking and mitigation planning

---

## Risk Register

| Risk ID | Risk | Severity | Status | Mitigation |
|---------|------|----------|--------|------------|
| SR-001 | HeyGen API key exposed in chat transcript | 🔴 Critical | PENDING | Rotate key at HeyGen dashboard |
| SR-002 | GitHub PAT exposed in environment / logs | 🔴 Critical | PENDING | Revoke PAT, regenerate, store only in `.env` |
| SR-003 | `.env` file included in zip bundle | 🟠 High | PENDING | Remove before sharing any zip |
| SR-004 | Public repo contains "Private Repository" language | 🟡 Medium | ✅ Fixed | README updated |
| SR-005 | SIA-256 overclaims ("immutable", "cryptographic") | 🟠 High | PENDING | Audit and relabel all proof claims |
| SR-006 | No pre-commit secret scanning | 🟡 Medium | PENDING | Add `gitleaks` or `trufflehog` pre-commit |
| SR-007 | No CI secret scanning | 🟡 Medium | PENDING | Add GitHub secret scanning / push protection |

---

## Credential Rotation Status

| Credential | Status | Date | Notes |
|------------|--------|------|-------|
| HeyGen API Key | ⬜ Pending | — | Must be rotated at HeyGen dashboard |
| GitHub PAT | ⬜ Pending | — | Must be revoked and regenerated |
| GITHUB_TOKEN (env) | ⬜ Pending | — | Must be removed from env |
| PHOENIX_GITHUB_PAT | ⬜ Pending | — | Must be removed from env |

---

## Next Actions

1. Rotate HeyGen API key
2. Revoke and regenerate GitHub PAT
3. Remove `.env` from any shared bundles
4. Add pre-commit secret scanning
5. Audit all "SEALED" / "cryptographic" claims

---

*Designed and Architected by Nathan Poinsette · NMCP3*  
*Echo Universe · Sovereign Intelligence Division · 2026*
