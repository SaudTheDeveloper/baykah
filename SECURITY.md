# Public repository security guidelines

This repository is public by design. Do not post sensitive data in issues, pull requests, commits, files, comments, screenshots, attachments, or workflow logs.

Never publish personal or private service usernames, internal/private project URLs, webhook receiver endpoints, access tokens, API keys, OAuth secrets or client IDs, signing keys, private account identifiers, or customer information.

Use placeholders such as `********` for private identifiers and `https://example.invalid/` for examples. Replace data **before** publication; editing an issue after publication does not guarantee its earlier revision is inaccessible.

If confidential details have been exposed, remove the original public artifact where possible, check revisions and other copies, and rotate any affected credentials. Repository workflows automatically lock new issue conversations; this does **not** make issues private and does **not** stop a public title or body being read.

Do not store production credentials in this repository. Use the relevant platform secret manager, keep application access limited to the minimum necessary permissions, and avoid unnecessary third-party application installations.

The repository's automation does not connect to, modify, or administer any external store or production service.
