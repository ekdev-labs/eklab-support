# Eklab support

Public issue tracking for Eklab, a component library for native HTML, Angular and React.
The implementation is maintained privately. This repository contains support material, not the library source code.

## Get help or share a request

[Open an issue](https://github.com/ekdev-labs/eklab-support/issues/new/choose) and choose:

- **Support question** — help with installation, themes or using Eklab.
- **Bug report** — behavior that does not work as expected.
- **Component request** — a component you would like Eklab to provide.
- **Feature request** — an improvement to an existing capability or documentation.

Search existing issues first. A GitHub account is required to post or vote.

For bug reports, include the exact Eklab package versions, framework version, browser/OS and a minimal reproduction.
A short synthetic example in the issue is welcome; a separate reproduction repository is not required.
Explain what you expected and what actually happened.

Issues, comments and attachments are public. Remove credentials, personal information, customer code and confidential data before posting.
For a suspected vulnerability, use [private security reporting](SECURITY.md) instead.

## Vote for requests

Add a **👍 reaction to the issue's opening post** to support a request. Reactions on replies are not votes for the request.
If the request already exists, vote there instead of opening a duplicate or posting a “+1” comment.
Comments explaining a concrete use case or unmet need are welcome.

- [Most-voted open requests](https://github.com/ekdev-labs/eklab-support/issues?q=is%3Aissue%20is%3Aopen%20label%3Aenhancement%20sort%3Areactions-%2B1-desc)
- [Most-voted component requests](https://github.com/ekdev-labs/eklab-support/issues?q=is%3Aissue%20is%3Aopen%20label%3Acomponent-request%20sort%3Areactions-%2B1-desc)

Votes help us identify demand and prioritize work. The owner makes the final decision, considering usefulness,
accessibility, maintenance effort and technical readiness. A vote count is not a delivery commitment.

## What happens next

Reports are reviewed for reproducibility and duplicates. We may request more information.
Confirmed fixes are developed and tested privately. When a fix is released, its package version is recorded in the issue.
An issue marked `awaiting-release` has not yet been resolved in a distributed package.
We aim to respond quickly and deliver useful improvements promptly. Progress and release information are shared in the issue.
No guaranteed response or resolution time is offered.

## Contributions and access

Community participation happens through issues, comments and votes. Please use an issue for documentation corrections too.
We do not accept community pull requests or code contributions in this repository.
Only the owner's account has write access, and pull request creation is restricted to repository collaborators.
GitHub Actions is disabled in this public repository.

## Releases and examples

This support repository does not announce a product release by itself.
Verified installation instructions, release notes and examples will be added when the corresponding packages and components are available.

## Package names

Eklab uses one name across integrations:

| Package                     | Purpose                                |
| --------------------------- | -------------------------------------- |
| `@ekdev-labs/eklab`         | Framework-neutral core and native HTML |
| `@ekdev-labs/eklab-angular` | Angular integration                    |
| `@ekdev-labs/eklab-react`   | React integration                      |
| `@ekdev-labs/eklab-themes`  | Themes and design tokens               |
| `@ekdev-labs/eklab-skills`  | Versioned consumer skills              |

These names describe the planned distribution. No npm release is announced here.
