# test-public-repo

## Purpose

This repository is a safe, public canary used to validate the Falcon Dev
Team's automated Linear-to-PR-to-merge workflow end to end. It contains no
production code and no user-facing product — it exists solely so the
pipeline (issue refinement, implementation, review, and merge) can be
exercised safely against a real GitHub repository without risk to any real
product.

## Verification

To confirm the workflow is actively functioning, check either of the
following:

- This repository's [Linear project](https://linear.app/matty-v), which
  tracks every issue that has moved through the pipeline (Triage → Ready to
  Build → In Review → Done).
- This repository's GitHub [issue](https://github.com/matty-v/test-public-repo/issues)
  and [pull request](https://github.com/matty-v/test-public-repo/pulls)
  history, which records every automated change the pipeline has produced.
