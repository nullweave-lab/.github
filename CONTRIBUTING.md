# Contributing to Nullweave Research

Thank you for contributing to Nullweave Research. The project accepts research notes, specifications, implementation changes, tests, documentation, and reproducibility reports.

## Before opening a contribution

1. Search existing issues and pull requests.
2. Keep one pull request focused on one technical objective.
3. Do not include credentials, private keys, tokens, personal data, production endpoints, proprietary rule sets, patent-confidential material, or unresolved exploitation chains.
4. For a suspected vulnerability, follow `SECURITY.md` instead of opening a public issue.

## Evidence labels

Technical claims should use one of these labels where practical:

- **Established:** supported by an authoritative specification, reproducible implementation behavior, or cited prior work.
- **Engineering assumption:** a condition required by a design or experiment.
- **Research hypothesis:** a testable proposition not yet established.
- **Experimental result:** an observation with documented setup and method.
- **Open question:** unresolved and not presented as a conclusion.

## Pull request requirements

Every pull request should state:

- what changed;
- the design basis;
- the security boundary and threat assumptions;
- unresolved questions or limitations;
- dependencies on other repositories or specifications;
- how the change was verified.

Code changes should include tests where feasible. Protocol changes should include or update test vectors. Parsers and verifiers must treat inputs as adversarial.

## Research and citation quality

Use primary sources where possible: standards, official platform documentation, peer-reviewed papers, or directly reproducible source code. Do not invent citations, experimental data, institutional affiliations, or security properties.

## Licensing

Licensing is repository-specific. Do not assume that documentation without an explicit license may be reused under the license of a related code repository. Contributions are accepted under the license and contribution terms stated by the target repository.
