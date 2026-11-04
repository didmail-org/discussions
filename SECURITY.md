# Security

This repository hosts public forum guidance and templates. Never put private
keys, recovery phrases, access tokens, real mail, local databases or exploitable
vulnerability details into discussions or pull requests.

## Report privately

For a vulnerability affecting this repository, use
[GitHub private vulnerability reporting](https://github.com/didmail-org/discussions/security/advisories/new).
Private reporting is enabled for this repository. Include a concise description,
affected version or URL, impact and a safe reproduction. Do not attach live
credentials or third-party private data.

For a protocol, server or client vulnerability, follow the affected repository's
security policy. Start with the
[project security guidance](https://github.com/didmail-org/overview/blob/main/SECURITY.md)
if ownership is unclear. If a private channel is unavailable, ask a maintainer
for one without disclosing the vulnerability publicly.

If you accidentally publish a secret, revoke or rotate it through the owning
service promptly and contact a maintainer to coordinate content cleanup.
Deleting the post or editing Git history alone does not invalidate an exposed
credential.

Maintainers address security fixes on the current default branch. This community
repository does not certify the security or production readiness of DIDMail,
ARC, or third-party integrations discussed here.
