# superagent-playground

English | [简体中文](README.md)

A playground repository for validating the end-to-end flow of
[`dsh-superagent`](https://github.com/deepseek-ai/deepseek-harness).

## About

This repository does not contain application code. It serves as a **stable,
low-risk target** for exercising the full `dsh-superagent` pipeline — from
receiving a human request to publishing a reviewed change — so that the
pipeline itself can be verified end to end.

Changes made here are intentionally small and easy to review, because the point
is the flow, not the content.

## What this repository is used for

- Verifying that a request raised in a chat tool (for example Feishu) is picked
  up, planned and executed.
- Verifying that changes are delivered as pull requests, complete with review
  and CI.
- Verifying that questions and results are reported back to the person who
  asked, in the original conversation.
- Providing a place to reproduce and debug issues in the pipeline without
  touching production repositories.

## Repository layout

| Path | Purpose |
| --- | --- |
| `README.md` | Chinese documentation (the default README shown on GitHub). |
| `README.en.md` | English documentation (this file). |

## Language versions

| Language | File |
| --- | --- |
| 简体中文 | [`README.md`](README.md) |
| English | [`README.en.md`](README.en.md) |

The Chinese version is the default `README.md`, so GitHub renders it on the
repository home page. The English version is kept in a separate file and linked
from the top of both documents. Please keep the two versions in sync: when one
changes, update the other in the same pull request.

## Contributing

1. Create a branch for your change.
2. Keep each pull request focused on a single, small change.
3. Open a pull request against the default branch and describe what you
   changed and how you checked it.
4. If you edit one language version, update the other one as well.

## License

No license has been declared for this repository yet. Until one is added, the
code is not licensed for use, modification or distribution by third parties.
