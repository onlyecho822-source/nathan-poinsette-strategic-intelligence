# Research Links — Consolidated Intelligence

**All conversation windows consolidated into one reference document**

---

## Conversation Windows

### Window 1: Claude.ai — Credential Audit & HeyGen Integration
**URL:** https://claude.ai/share/bf6d2028-9dfb-4c67-bd26-32a539f6da85  
**Date:** Jun 18, 2026  
**Key Topics:**
- 🔴 **CRITICAL:** Live HeyGen API key exposed in plaintext
- 🔴 **CRITICAL:** Live GitHub PAT (`github_pat_11B2DV…qIg`) in `newPAT.txt` — NOT in `.gitignore`
- 🟡 **HIGH:** SIA-256 verification broken on entries >200 characters
- 🟡 **HIGH:** 181 instances of "SEALED/immutable/cryptographic" labels without proof
- ✅ **GOOD:** `talkingFace.ts` has correct v3 HeyGen integration
- 🔴 **BAD:** `heygen_wrapper.py` is broken v2 duplicate (uses 404 path)
- ✅ **SOUND:** `governance_atoms.md` and `core_invariant.md` are disciplined work
- 📊 **FINDING:** Convergent thinking (rigorous) vs. divergent theater (overclaimed)

**Key Recommendation:** Delete Python wrapper, keep TS version. Fix SIA-256. Rotate credentials immediately.

---

### Window 2: DeepSeek — [Content Restricted]
**URL:** https://chat.deepseek.com/share/apxk3qowdxnsjeyrqv  
**Date:** Jun 18, 2026  
**Status:** Access blocked (cookies-only page)

**Action:** Re-share or provide summary manually

---

### Window 3: ChatGPT — [Content Restricted]
**URL:** https://chatgpt.com/share/6a39553b-bbe4-83ea-93df-384ba6d1a505  
**Date:** Jun 18, 2026  
**Status:** Access blocked (requires login)

**Action:** Re-share or provide summary manually

---

### Window 4: ChatGPT — [Content Restricted]
**URL:** https://chatgpt.com/share/6a395565-cda4-83ea-bcf1-fd05c2b79ca7  
**Date:** Jun 18, 2026  
**Status:** Access blocked (requires login)

**Action:** Re-share or provide summary manually

---

### Window 5: ChatGPT — [Content Restricted]
**URL:** https://chatgpt.com/share/6a3955e9-7e80-83ea-851e-3fcaa8bb68ac  
**Date:** Jun 18, 2026  
**Status:** Access blocked (requires login)

**Action:** Re-share or provide summary manually

---

## Consolidated Findings

### Critical Issues (Do Today)
1. **Rotate HeyGen API key** — Exposed in plaintext, revoke and create new
2. **Rotate GitHub PAT** — Exposed in `newPAT.txt`, add to `.gitignore`, revoke old
3. **Fix SIA-256 verification** — Fails on entries >200 chars (hash full, verify truncated)

### High Priority (This Week)
1. **Delete HeyGen Python wrapper** — It's a broken v2 duplicate of working TS code
2. **Audit "SEALED" claims** — 181 instances without proof, relabel or prove each one
3. **Consolidate research streams** — Stop using 5 chat windows, use this repo instead

### Medium Priority (Next 2 Weeks)
1. **Design org structure** — Divisions, sections, roles, approval chains
2. **Build command center** — Dashboard, role management, decision workflow
3. **Integrate frameworks** — Wire ADAM model and 7-lens pipeline into Echo Nexus

---

## Frameworks & Models (From All Windows)

### ADAM Framework (8-Layer Human Model)
**Source:** Nathan's original intellectual architecture  
**Status:** ✅ Sound, convergent, falsifiable  
**Use:** Diagnostic tool for organizational health analysis

1. Structural — Load-bearing scaffold
2. Electrical — Signals, bioelectricity
3. Chemical — Hormones, neurotransmitters
4. Signal — Communication pathways
5. Genetic — DNA expression, epigenetics
6. Mechanical — Movement, force, leverage
7. Thermodynamic — Energy budget, entropy
8. Perceptual — Subjective experience, qualia

### 7-Lens Decision Pipeline
**Source:** Echo Veritas strategic decision engine  
**Status:** ✅ Implemented in Python, needs web integration  
**Use:** Strategic decision evaluation framework

Research → Evidence → Falsification → Monetization → Execution → Synthesis → Reality Check → Proof Hash

### Governance Model — First Bond
**Source:** governance_atoms.md  
**Status:** ✅ Stated, 🔴 Violated (credentials exposed)  
**Use:** Organizational invariants and guardrails

- Gate A: Credential Quarantine
- Gate B: Proof Integrity
- Gate C: Audit Trail
- Gate D: Falsification

---

## Systems & Integrations

### HeyGen Integration
- **Working:** `talkingFace.ts` (v3, correct)
- **Broken:** `heygen_wrapper.py` (v2, 404 path)
- **Action:** Delete Python, keep TS
- **Status:** 🟡 NEEDS CONSOLIDATION

### OpenAI LLM Routing
- **Current:** Using user's API key (sk-proj-...)
- **Status:** ✅ WORKING (but key has no credits)
- **Fallback:** Manus built-in LLM
- **Action:** Add credits or switch to fallback

### SIA-256 Proof Chain
- **Current:** Local SHA-256 linked list
- **Status:** 🔴 BROKEN (verification fails >200 chars)
- **Fix:** Add GPG signing or external anchor
- **Action:** Implement before claiming "cryptographic proof"

### MCP Connectors
- **Available:** HeyGen MCP (no key needed)
- **Status:** ✅ READY
- **Action:** Consider using instead of raw API key

---

## Organizational Structure (To Be Designed)

**Current State:** Solo (Nathan + ECHΩ)  
**Target State:** Military-style command structure with divisions, sections, roles

**Proposed Divisions:**
- HQ / Strategic
- Operations
- Intelligence
- Commerce
- Engineering
- Governance

**Key Decision:** Who fills each role? (Human, AI agent, or hybrid?)

---

## Next Steps

1. **Consolidate all research** — Pull summaries from DeepSeek & ChatGPT windows
2. **Update STATUS_LOG.md** — Real-time tracking of all systems
3. **Design org chart** — Divisions, sections, roles, approval chains
4. **Build command center** — Dashboard, RBAC, decision workflow
5. **Integrate frameworks** — ADAM model, 7-lens pipeline, proof system

---

## Access & Maintenance

- **Repository Owner:** Nathan Poinsette
- **Last Updated:** Jun 18, 2026
- **Next Review:** Jun 22, 2026
- **Status:** 🟡 ACTIVE — Awaiting org structure design

---

*Sealed: SIA-256 ∇θ*
