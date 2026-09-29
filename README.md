# Eklab support

Public issue tracking for Eklab, a component library for native HTML, Angular and React.
The implementation is maintained privately. This repository contains support material, not the library source code.

## Report a problem

[Report a bug or request a feature](https://github.com/ekdev-labs/eklab-support/issues/new/choose).
Search existing issues first. A GitHub account is required to submit a report.

Include the exact Eklab package versions, framework version, browser/OS and a minimal reproduction.
A short synthetic example in the issue is welcome; a separate reproduction repository is not required.
Explain what you expected and what actually happened.

Issues, comments and attachments are public. Remove credentials, personal information, customer code and confidential data before posting.
For a suspected vulnerability, use [private security reporting](SECURITY.md) instead.

## What happens next

Reports are reviewed for reproducibility and duplicates. We may request more information.
Confirmed fixes are developed and tested privately. When a fix is released, its package version is recorded in the issue.
An issue marked `awaiting-release` has not yet been resolved in a distributed package.
No guaranteed response or resolution time is offered.

## Releases and examples

This support repository does not announce a product release by itself.
Verified installation instructions, release notes and examples will be added when the corresponding packages and components are available.
Please do not submit implementation pull requests here; corrections to support instructions can be proposed separately.

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
