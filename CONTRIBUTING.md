# Contributing to CCMMF

<!-- 
TODO:
- Add preferred languages
- Code style
- What contributions go to PEcAn or SIPNET, what to CCMMF
  - Types of output: workflow, documentation, sipnet, monitoring
- Guidance for tests, documentation, NEWS
- Authorship, CITATION.cff
- what goes in private vs public discussions?
-->

The California Cropland Monitoring and Modeling Framework (CCMMF) is an integrated pipeline
built on the [SIPNET biogeochemistry model](https://github.com/pecanproject/sipnet) and 
[PEcAn](https://github.com/pecanproject/) modeling, informatics, and statistical inference workflow 
engine.

This is a guide for contributors and users of the software.

> For an introduction to using GitHub and Slack for communication within the CCMMF community, see [GITHUB_SLACK_INTRODUCTION.md]


## How to contribute

We welcome contributions from the community to help improve and apply CCMMF including documentation, 
software, and data products. 

### Communication

Feel free to reach out directly with ideas, questions, and suggestions through 
our [GitHub Discussions](https://github.com/orgs/ccmmf/discussions) and join the #ccmmf channel 
in the [PEcAn Project Slack](https://join.slack.com/t/pecanproject/shared_invite/enQtMzkyODUyMjQyNTgzLWEzOTM1ZjhmYWUxNzYwYzkxMWVlODAyZWQwYjliYzA0MDA0MjE4YmMyOTFhMjYyMjYzN2FjODE4N2Y4YWFhZmQ).

### Bug Reports and Feature Suggestions

If you find bugs or would like to request a feature, please open an issue in the appropriate GitHub repository and select the approprate bug report or feature request template.

For **bugs**, please provide a clear description of the bug and steps to reproduce it. If you find a bug or issue in R, 
please use the [reprex](https://reprex.tidyverse.org/) package to generate a reproducible example.

To request a new **feature**, it will often be helpful to use Slack or GitHub Discussions to flesh out and brainstorm ideas. A good feature request will include a clear description of the feature and how it would be used.

## Code of Conduct

This project has a [Code of Conduct](https://github.com/ccmmf/.github/blob/main/CODE_OF_CONDUCT.md) 
that provides a framework for a welcoming and collaborative environment. Contributors are expected to 
read and agree this code.

## Code Contributions

We accept code contributions via Pull Requests (PRs) to GitHub repositories. GitHub provides excellent documentation of this process, e.g. [Creating a Pull Request from a Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).

All PRs must be reviewed by a member of the core CCMMF team and 
pass integration tests prior to being merged.
The general PR workflow is:

1. Identify an open issue, create a new feature request, or start a discussion.
1. Fork the repository.
2. Create a new branch.
3. Make changes.
4. Write tests.
5. Update documentation.
6. Push branch to your forked repository.
7. Open a pull request to the 'develop' branch of the origin repository.
8. Ensure tests pass.
9. Address any questions or changes requested during review.

Once your contribution is merged it is time to elebrate!

## Licenses and Copyright

Contributions to CCMMF will be released under permissive BSD 3-Clause (code), CC-BY (documentation). 
Contributions to PEcAn are released under BSD 3-Clause or compatible 
(UIUC NCSA) license.
