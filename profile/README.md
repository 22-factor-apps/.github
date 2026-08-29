# The Twenty-Two-Factor App

We maintain an evidence-oriented field guide for software that must remain
understandable, trustworthy, changeable, and operable after it meets production.

The project keeps ten durable constraints from the original Twelve-Factor App,
retires two mechanisms whose intent now has a broader home, and adds twelve
modern obligations covering interfaces, security, observability, supply chain,
resilience, data, infrastructure, delivery, compatibility, ownership, cost, and
sustainable operation.

## Start here

- **[Read the field guide](https://22-factor-apps.github.io/)** — all 22
  commandments, boundaries, failure modes, litmus tests, and research lineage.
- **[Compare the manifestos](https://22-factor-apps.github.io/research)** — the
  original twelve alongside Fifteen-Factor, Reactive, SRE, Chaos, DORA,
  Well-Architected, Secure by Design, Local-first, FinOps, sustainable software,
  and AI-oriented extensions.
- **[Audit a project](https://22-factor-apps.github.io/audit)** — discover
  repository and organization evidence, then record a contextual assessment.

## Repositories

| Repository | Responsibility |
|---|---|
| [`22-factor-apps.github.io`](https://github.com/22-factor-apps/22-factor-apps.github.io) | Canonical Astro site, 22 source documents, generated factor catalog, and assessment template |
| [`22-factor-apps-audit`](https://github.com/22-factor-apps/22-factor-apps-audit) | Read-only Rust CLI, versioned audit policy, assessment validator, and JSON contracts |
| [`.github`](https://github.com/22-factor-apps/.github) | Organization profile, ownership, security, and contribution defaults |

## How we work

The commandments are pressures, not a maturity score. Automation may locate
evidence, but it cannot infer architectural truth from filenames. Claims stay
attached to a factor, boundary, rationale, durable evidence URL, owner, review
date, and follow-up.

The site ships as static HTML with no client-side telemetry. The auditor is
read-only, accepts GitHub credentials only through the environment, and redacts
credentials embedded in HTTPS Git remotes before producing reports.

Questions, counterexamples, and research-backed disagreement are welcome. A
methodology stays useful by remaining open to evidence.
