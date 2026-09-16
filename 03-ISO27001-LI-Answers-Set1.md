# ISO/IEC 27001:2022 Lead Implementer — Answers, Set 1
### Topic 1: Context of the Organization & ISMS Scope (Clause 4.1–4.4)

For each answer: reasoning first, clause reference, then a confidence tag.
🟢 = high confidence, cross-checked · 🟡 = generally reliable but recommend confirming against her actual course material/standard copy for exact phrasing.

---

**A1.** Not justifiable on the stated grounds alone. Clause 4.3 requires scope to be determined considering interfaces and dependencies between activities inside and outside the proposed boundary — not merely whether a unit directly touches sensitive data. Marketing sits on the same IT Infrastructure that Payments relies on, and shares organizational governance, staff, and possibly network segments. "Doesn't touch sensitive data" addresses only one risk dimension; it ignores shared infrastructure dependency, which is exactly what 4.3 asks the organization to examine. A defensible exclusion would need to show the interfaces are genuinely segregated (separate infrastructure, separate governance, documented boundary) — the scenario as given (shared IT Infrastructure division) suggests they aren't. The correct implementer response is to push back and ask for evidence of segregation before accepting the exclusion.
*Clause reference: 4.3.* 🟢

**A2.** This is a Clause 4.2 gap. 4.2 doesn't just require identifying interested parties — the 2022 revision explicitly added the requirement to determine *which of their requirements will be addressed through the ISMS*. A general list of interested parties without mapping specific requirements (contract clauses, regulatory obligations) to ISMS scope/controls is incomplete. This is one of the most commonly tested 2022-specific additions, so it's worth remembering by name.
*Clause reference: 4.2.* 🟢

**A3.** Clause 4.3 requires considering interfaces and dependencies between the organization's activities and those performed by other organizations — this explicitly covers outsourced/third-party arrangements, not just internally-run infrastructure. "We don't operate the servers" doesn't remove the dependency; the organization still depends on that provider for confidentiality, integrity and availability of in-scope information. The correct approach isn't to exclude the cloud provider wholesale, but to: (a) keep the dependency in view when scoping, (b) manage it through supplier/ICT relationship controls (this is an Annex A theme we'll get to — Topic 9), and (c) reflect the shared responsibility boundary in the SoA rather than pretending it doesn't exist. Total exclusion "because we don't own the hardware" is the kind of answer BSI-style questions are designed to catch you on.
*Clause reference: 4.3.* 🟢

**A4.** Both findings should feed into the 4.1 context analysis and then carry forward into scope (4.3) and risk assessment (6.1.2/8.2). The upcoming legislation is an external issue that likely narrows what "compliant" looks like for the ISMS and may expand which interested-party requirements (4.2) need addressing. The information-sharing culture is an internal issue that should surface as a candidate risk in the risk assessment (informal access bypassing formal requests is a control-effectiveness gap, likely mapping to access control and awareness topics we'll cover later). Neither of these should be scoped *out* to make the ISMS simpler — 4.1 findings exist precisely to be carried into the rest of the PDCA cycle, not filed away.
*Clause reference: 4.1, with downstream links to 4.2, 4.3, 6.1.2.* 🟢

**A5.** **C.**
- A is wrong — exclusions are permitted, not banned.
- B is wrong — there's no headcount threshold in the standard; that's not how 27001 scoping works.
- D is wrong — scope is the organization's own determination (documented and justified by them), not something the certification body decides on their behalf, though the auditor will scrutinize it.
- C matches Clause 4.3's actual test: justification must be rooted in the 4.1–4.3 analysis, and the exclusion cannot cut across genuine interfaces/dependencies with in-scope activities.
*Clause reference: 4.3.* 🟢

---

### Score yourself
- 5/5 correct with solid reasoning → Topic 1 can move to 🟢 Solid in the concept tracker; next session starts Topic 2.
- 3–4/5, or right answer but shaky reasoning → 🟡 stays in progress; I'll fold in 1–2 Topic 1 questions into the Topic 2 set as a check.
- ≤2/5 → 🔴 flagged weak; next session repeats Topic 1 with a fresh set before moving on.

Let me know how she scored (and where the reasoning felt shaky, even on correct answers) and I'll update the concept tracker and build Set 2.
