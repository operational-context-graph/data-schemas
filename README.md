[![CodeQL](https://github.com/operational-context-graph/data-schemas/actions/workflows/codeql.yml/badge.svg)](https://github.com/operational-context-graph/data-schemas/actions/workflows/codeql.yml)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/operational-context-graph/data-schemas/badge)](https://securityscorecards.dev/viewer/?uri=github.com/operational-context-graph/data-schemas)
[![REUSE status](https://api.reuse.software/badge/github.com/operational-context-graph/data-schemas)](https://api.reuse.software/info/github.com/operational-context-graph/data-schemas)

# data-schemas

## About this project

This repository is the schema authoring environment for the [Operational Context Graph (OCG)](https://github.com/operational-context-graph/operational-context-graph). It contains the versioned source artifacts that define the OCG data schema: JSON Schema definitions, JSON-LD context files, source mappings, and ontology alignments.

Schema changes are proposed through pull requests. A CI pipeline validates artifacts and compatibility rules before publication. Approved releases are imported into the Schema Introspection API, which serves as the read-only projection of published schema versions.

The repository does not contain runtime services or application code. Its artifacts govern the structure and semantics of all data stored and exchanged within the [OCG](https://github.com/operational-context-graph/operational-context-graph).

## Requirements and Setup

No build toolchain is required to contribute schema definitions. Validation tooling (JSON Schema validators, JSON-LD processors) will be documented here when the CI pipeline is finalized.

## Support, Feedback, Contributing

This project is open to feature requests/suggestions, bug reports etc. via [GitHub issues](https://github.com/operational-context-graph/data-schemas/issues). Contribution and feedback are encouraged and always welcome. For more information about how to contribute, the project structure, as well as additional contribution information, see our [Contribution Guidelines](https://github.com/operational-context-graph/.github/blob/main/CONTRIBUTING.md).

## Security / Disclosure

If you find any bug that may be a security problem, please follow our instructions at [in our security policy](https://github.com/operational-context-graph/.github/blob/main/SECURITY.md) on how to report it. Please do not create GitHub issues for security-related doubts or problems.

## Code of Conduct

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone. By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/operational-context-graph/.github/blob/main/CODE_OF_CONDUCT.md) at all times.

## Licensing

Copyright 2026 SAP SE or an SAP affiliate company and Operational Context Graph contributors. Please see our [LICENSE](./LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/operational-context-graph/data-schemas).
