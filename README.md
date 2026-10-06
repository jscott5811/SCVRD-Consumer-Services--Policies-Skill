# SCVRD Consumer Services Policies Skill

An AI skill that helps people understand the South Carolina Vocational
Rehabilitation Department's (SCVRD) Consumer Services Policies — the rulebook
for VR services in South Carolina.

## What it does

When asked about SCVRD vocational rehabilitation, the skill:

- Explains the VR process: application, eligibility, the Individualized Plan
  for Employment (IPE), services, and case closure.
- Points to the exact policy (by CSP number) and links the published SCVRD
  document.
- Explains the money rules: the financial need test (CSP 3.10) and
  comparable services and benefits (CSP 3.20).
- Explains consumer rights and the complaint/appeal chain (CSP 1.20):
  Area Supervisor review → Client Assistance Program → mediation/impartial
  hearing.
- Includes a plain-language consumer process checklist.

## Sources

**SCVRD is the only original documentation source.** Every factual claim
traces to SCVRD's published Consumer Services Policies (rev. 07-2025) at
https://www.scvrd.net/238/Consumer-Services-Policies and the individual
policy documents listed in `skills/scvrd-consumer-services-policies/references/verified-sources.md`.
The skill summarizes and links; it does not reproduce policy text.

## Install

```bash
npx skills add jscott5811/SCVRD-Consumer-Services-Policies-Skill
```

## Structure

```
skills/scvrd-consumer-services-policies/
  SKILL.md                          # the skill: process, topic lookup, money rules, grounding rules
  references/verified-sources.md    # every SCVRD source used (links + effective dates)
  references/policy-index.md        # CSP section index with one-line summaries and links
  references/consumer-process-checklist.md  # plain-language checklist for consumers
```

## License

MIT
