# Contributing

This repository maintains DIDMail's organization discussion guidance and forms.
Use the [forum](https://github.com/orgs/didmail-org/discussions) for questions and
ideas, and submit pull requests here to improve these versioned files.

## Helpful discussions

Search for an existing thread, choose the closest category, and describe the
outcome you need. For a technical question, include the relevant component,
exact version, environment, expected/actual behavior and a minimal reproduction.
Distinguish implementation facts, local experiments and proposed behavior.

You may write in Chinese or English. English is authoritative for engineering
documentation in this repository. Translation and wording corrections are welcome.
If AI helped prepare a report, verify its claims and include the actual evidence;
label unverified output rather than presenting it as a completed test.

Stay on topic, reply in the existing thread, and mention only people whose input
is relevant. Do not repeatedly ping individuals for a response. When a Q&A is
resolved, mark the useful reply as the answer and describe any version limits.

Never post credentials, recovery phrases, private keys, real mail or unredacted
runtime databases/logs. See [SECURITY.md](SECURITY.md) for vulnerability reporting
and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for community expectations.

## Changes to repository files

1. Make a focused branch and describe the reader-facing change in your pull request.
2. Check local links, category URLs, spelling and `git diff --check`.
3. For a category form, validate its YAML and match the filename to the live
   category slug. Keep at least one non-Markdown field. Polls do not support
   category forms. Do not add nonexistent labels or mention accounts automatically.
4. Preserve security guidance, source attribution and applicable license notices.

Category forms live in `.github/DISCUSSION_TEMPLATE/`. They take effect from the
default branch; they do not rewrite existing discussions. Match the
[GitHub category form syntax](https://docs.github.com/en/discussions/managing-discussions-for-your-community/syntax-for-discussion-category-forms).
This documentation-only repository does not require a root dependency workspace
or application build.

Original versioned contributions use Apache-2.0. Submit only material you are
entitled to contribute and retain third-party terms. Contributions must follow
the community conduct policy; a pull request is not permission to contact other
participants outside its stated purpose.
