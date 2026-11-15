# Contributing to nsw-organ-donation-sources

This repository holds a bounded NSW organ-donation source pack with primary documents and fallback links. Contributions should improve source identity, accurate documentation, reproducibility and correction of broken or misleading references.

## Before you start

Read [README.md](README.md), inspect the existing source layout and check open issues and pull requests. State whether a proposed change adds a source, replaces a retained version, corrects metadata or changes interpretation. Preserve the difference between original documents, extracted text and contributor commentary.

For bugs, provide the affected version or commit, environment, minimal reproduction, expected result and observed result. For a substantial proposal, describe the use case and compatibility impact before expanding implementation scope. Use existing issue templates when offered.

## Development and validation

Inspect [the existing workflows](.github/workflows) before selecting any automated retrieval or validation. No standalone local test command is documented in the README. For a source change, verify the publisher, title, date or version, original URL, retrieval limitations and the right to retain or redistribute the material.

When updating a file, retain enough provenance to identify the previous and replacement versions. Check any documented hash or filename references affected by the change. Open the relevant document to confirm its content matches its identity; successful download or a matching hash alone does not establish source accuracy or applicability.

Use primary sources for factual corrections, identify the precise passage supporting the change and record unresolved ambiguity. Keep policy statements, interpretation and recommendations distinct. For documentation-only edits, check links and readability. Do not add patient information, private correspondence or institutional records under the assumption that a public source pack authorises their publication.

## Pull requests

Create a focused branch from the current `main` branch and submit a pull request to this repository. Link the relevant issue or existing project task, explain the resulting behaviour, and update affected examples and documentation. Keep unrelated changes in separate pull requests.

Report executed commands, outcomes and the commit they validate. Identify unavailable checks and remaining limitations explicitly. Follow the repository's existing review and automated-check requirements; retain required gates and current ownership. Address findings and verify the final head before integration. Repository changes do not themselves authorise a release or external operational action.

## Security, rights and conduct

Follow the [security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Use private vulnerability reporting if available; otherwise request a private contact without publishing vulnerability details. Keep credentials, personal information and restricted source material out of issues, fixtures, logs and artifacts.

Preserve existing attribution and third-party terms. This guide does not grant a licence; clarify any unclear redistribution rights before contributing external material. Follow the [code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md) and keep technical discussions respectful.

## Basis for this guide

This guide follows [GitHub's contribution-guideline guidance](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) and the contribution-process and testing principles in [OpenSSF Best Practices](https://www.bestpractices.dev/en/criteria). It does not assert certification.
