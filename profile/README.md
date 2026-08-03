# Nullweave Research

Nullweave Research is an independent open research organization studying verifiable runtime integrity, remote attestation, and the relationship between physical device state and digital trust.

Our primary public research program is **PARC** — **Physical-Anchored Runtime Continuity**. PARC investigates how an Android application and a verifier can reason about device state, boot state, runtime continuity, freshness, and evidence provenance without reducing trust to a single local detection result.

## Research principles

- **Evidence, not slogans.** Security claims must state their assumptions, scope, failure modes, and uncertainty.
- **Layered trust.** Hardware-backed keys, boot-state evidence, runtime measurements, protocol freshness, and verifier policy are distinct layers with distinct control boundaries.
- **Reproducibility.** Public claims should be backed by specifications, test vectors, reference implementations, or repeatable experiments.
- **Adversarial review.** Negative results, bypass classes, and limitations are part of the research record.
- **Responsible disclosure.** We do not publish unresolved exploitation chains or production-sensitive countermeasure details.

## Public repositories

| Area | Repository | Status |
|---|---|---|
| Program overview | `android-runtime-integrity-platform` | Draft |
| Theory | `matter-anchored-computing` | Research draft |
| Protocol | `parc-spec` | Not yet specified |
| Proof generation | `parc-proof` | Initial skeleton |
| Android SDK | `parc-android-sdk` | Initial skeleton |
| Native probes | `parc-native-probes` | Initial skeleton |
| Reference verifier | `parc-verifier` | Initial skeleton |
| Test laboratory | `parc-test-lab` | Initial skeleton |
| Paper | `parc-paper` | Pre-draft |
| Documentation | `parc-docs` | Initial skeleton |

## Scope and limitations

The public work is experimental. It is not a certification program, a warranty of device trustworthiness, or a claim that compromise can be made impossible. A clean result from any probe is not proof of a trustworthy device, and detection of a modification is not by itself a complete appraisal of risk.

Public repositories contain theory, protocols, auditable reference code, and sanitized experiments. Production policy engines, private risk models, operational infrastructure, unresolved bypass details, credentials, and patent-confidential material are outside the public scope.

## Contributing and security

Read the organization-wide [contribution guide](../CONTRIBUTING.md), [security policy](../SECURITY.md), and [code of conduct](../CODE_OF_CONDUCT.md) before opening a contribution.
